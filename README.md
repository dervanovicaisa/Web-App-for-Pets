# Cat Adoption & Community Platform

A full-stack web application developed as my **Bachelor thesis project**, built with PHP, MySQL, JavaScript, HTML/CSS and Bootstrap.

The goal of the application was to create a platform for displaying and managing cats available for adoption, while also providing community and content features such as user profiles, posts, comments and search.

## Features

- User registration and login
- Session-based authentication
- User profiles
- User and administrator roles
- Cat management
- Display of cats available for adoption
- Create, edit and delete operations
- Posts and comments
- Search functionality
- Content management
- Contact functionality
- Limited/paginated content loading
- Responsive user interface

## Technologies

### Backend

- PHP
- MySQL

### Frontend

- JavaScript
- HTML
- CSS
- Bootstrap

## Architecture

The application follows a traditional server-rendered PHP web application structure.

It can be viewed through three main responsibilities:

- **Presentation layer** — HTML, CSS, Bootstrap and JavaScript are used for the user interface and client-side interactions.
- **Application logic** — PHP handles requests, authentication, sessions, validation and application behaviour.
- **Data layer** — MySQL stores users, cats, posts, comments and other application data.

PHP connects the user-facing pages with the database and performs the required operations based on user actions and permissions.

## Database

The application uses a relational MySQL database to persist its data.

The database supports the main entities needed by the application, including:

- Users and profiles
- Cats
- Posts
- Comments
- Application content

The application performs standard create, read, update, delete and search operations against this data.

## Authentication & Authorization

The application includes user authentication and role-based functionality.

Users can register and log in, with passwords stored using password hashing rather than plain text. PHP sessions are used to maintain the authenticated state between requests.

Regular users and administrators have different levels of access, with additional management functionality available to administrators.

## Application Flow

A typical request follows this flow:

1. A user opens a page, performs an action or submits a form.
2. PHP receives and processes the request.
3. The application checks the current session and permissions where required.
4. PHP reads or updates the appropriate data in MySQL.
5. The resulting page or updated content is returned to the user.

JavaScript is used where additional client-side interaction is needed.

## Main Functionality

### Cat Adoption

The application displays cats, including cats available for adoption, and provides functionality for managing their information.

Administrative functionality supports creating, editing and deleting cat records.

### User Management

Users can register, log in and manage their profiles.

Authentication state is maintained using PHP sessions, while role-based functionality separates regular user access from administrative functionality.

### Community Content

The platform includes posts and comments, allowing users to interact with application content.

Administrative functionality is also available for managing content where required.

### Search and Content Loading

Users can search for relevant content within the application.

Content loading is limited/paginated instead of loading all available records at once.

## What I Worked On

As this was a Bachelor thesis project, I worked across both the frontend and backend parts of the application, including:

- PHP backend logic
- MySQL data structure and database operations
- Authentication and session management
- User and administrator permissions
- CRUD functionality
- Cat/adoption management
- Posts, comments and content management
- Search
- JavaScript functionality
- Responsive UI with Bootstrap

## What I Learned

This was one of my first larger full-stack projects and gave me practical experience with how the main parts of a web application work together.

Through the project, I gained experience with:

- Server-side development with PHP
- Relational databases and SQL
- Authentication and sessions
- Role-based functionality
- CRUD operations
- Data relationships
- Form handling
- Connecting frontend functionality with backend logic and data
- Structuring a larger web application

## Project Context

This application was developed as my **Bachelor thesis project** and represents my work and experience from that stage of my studies.

The repository is kept as part of my development history.
