# Group Chat Application -
A Sprint Boot application built using Java Socket Programming.

[![](https://img.youtube.com/vi/k36u4U7fp98/0.jpg)](https://www.youtube.com/watch?v=k36u4U7fp98)

Let's dive into the features and functionalities:

## Features :

- Client (user) can enter the Group Chat by entering Name in Popup window.
- Every new Client gets stored in "users" table in database with joining date-time stamp.
- Multiple users can send and receive message in same time, as well as read them on chat window.
- Client can end its session by clicking Exit button, but the server remains Live.
- Every message gets stored in "chat_backup" table in database with sender's name and id (with epoch).

## Technique :

- Used Socket Programming - created Sockets for communication between Clients and Server.
- Multi Threading for creating a Multi threaded Server, for connecting to multiple Clients at same time.
- Used MySQL Workbench for storing entities in database: users, chat_backup.
- JDBC for accessing the database and performing CURD operations.
- Java Spring Boot with MYSQL driver dependency.
