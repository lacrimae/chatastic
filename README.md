# Chatastic

## Overview

Chatastic is a chat application consisting of three microservices, each serving a different purpose.

## Microservices

1. [UI microservice](https://github.com/lacrimae/chatastic-ui). This microservice handles the user interface-related
   tasks, including displaying chat messages, managing user sessions, and handling user input.
2. [Login microservice](https://github.com/lacrimae/chatastic-login). This microservice is responsible for user
   authentication and authorization. It stores user information in a Redis database and communicates with the Core Chat
   microservice to retrieve user information when needed.
3. [Core Chat Microservice](https://github.com/lacrimae/chatastic-core). This microservice is responsible for managing
   the chat functionality of the application. It stores chat messages in a MongoDB database and communicates with the
   Login microservice to authenticate users and retrieve user information.

## Design

![](images%2Fchatastic%20-%20system%20design.png)
