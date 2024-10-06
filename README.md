# Web Forum Project

## Objectives

This project focuses on creating a web forum with the following features:
- Communication between users.
- Posts associated with categories.
- Ability to like/dislike posts and comments.
- Filtering posts by categories, created posts, and liked posts.

## Technologies

- **SQLite**: Used for storing forum data such as users, posts, comments, etc.
  - You must use at least one `SELECT`, `CREATE`, and `INSERT` query.
  - For better performance, create an Entity Relationship Diagram (ERD) to structure your database.
  - [SQLite Documentation](https://www.sqlite.org/docs.html) for further reference.

## Authentication

- Users must be able to register with an email, username, and password.
- Email must be unique, and return an error if already taken.
- Passwords must be stored securely, with encryption as a bonus task.
- Users must log in to create posts and comments.
- Implement user sessions with cookies and include session expiration.
- Use of **UUID** for user identification is a bonus.

## Communication

- Registered users can create posts and comments.
- Posts can be categorized into one or more categories.
- All posts and comments are visible to all users, but only registered users can interact (post, comment, like/dislike).

## Likes and Dislikes

- Only registered users can like/dislike posts and comments.
- The like/dislike counts are visible to all users.

## Filtering

Registered users can filter posts by:
- Categories (acts as subforums).
- Created posts.
- Liked posts.

## Docker

- This project uses **Docker**. Please refer to the [Docker basics](https://docs.docker.com/get-started/) to set up and run the application.

## Instructions

- Use **SQLite** for data management.
- Handle website errors and HTTP status codes.
- Implement best coding practices and error handling.
- Testing is recommended, with unit test files.

## Allowed Packages

- All standard Go packages are allowed.
- Additional allowed packages:
  - `sqlite3`
  - `bcrypt`
  - `UUID`

> **Note**: Do not use any frontend libraries or frameworks like React, Angular, or Vue.

## Learning Goals

By completing this project, you will learn:
- Web development basics: HTML, HTTP, Sessions, and Cookies.
- Using and setting up Docker: containerizing an application.
- SQL database manipulation.
- The basics of encryption for secure password storage.
