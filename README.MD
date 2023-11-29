# study-real-time-chat-api

This is a study project of real time chat with socket

## 📘 Tech Stack

**Server:**

- Typescript
- Node
- Express
- Docker
- Jest

## ⭐ Installation

Install my-project with npm

```bash
  docker-compose up --build
```

## ✅ Running Tests

To run tests, run the following command

```bash
  yarn run test
```

## 📌 Requirements

**User module**

Functional Requirements

- [ ] It must be possible to create a user with name, email and password
- [ ] It must be possible to edit a user's name or password
- [ ] It must be possible to delete a user
- [ ] It must be possible to read user information

Non-functional requirements

- [ ] The user password must be stored in JWT format
- [ ] User data must be stored in a mysql database

Business rules

- [ ] It should not be possible to create a user with the same email

**Chat module**

Functional Requirements

- [ ] It should be possible to start a chat with another user by passing their email
- [ ] It must be possible to list all chats of a user
- [ ] It should be possible to delete a chat

Non-functional requirements

- [ ] Chats data must be stored in a mysql database
