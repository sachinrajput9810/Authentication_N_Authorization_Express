# Express Authentication and Authorization

This repository demonstrates a basic setup for authentication and authorization in an Express.js application. The application includes features such as account creation, login, setting cookies, and logout, which involves removing cookies.

## Features

- **User Registration**: Allows new users to create an account by providing their username, email, password, and age. The password is securely hashed before being stored in the database.
- **User Login**: Authenticates existing users using their email and password. On successful login, a JWT (JSON Web Token) is generated and set as a cookie.
- **Cookie Management**: Manages user sessions using cookies. The JWT is stored in a cookie to keep the user logged in.
- **User Logout**: Clears the authentication cookie, effectively logging the user out.
