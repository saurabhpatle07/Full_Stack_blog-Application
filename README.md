# Full Stack Blog Application

The Full Stack Blog Application is a web application that allows users to create, read, update, and delete (CRUD) blogs. It supports multiple roles including user, admin, and editor, each with specific permissions. Users can register themselves, perform CRUD operations on their blogs, upload images, text, and links, and reset their passwords if forgotten. Pagination and sorting functionalities are also provided for better user experience.

## Features

- **User Authentication**: Implemented using JWT authentication for secure access to the application.
- **User Registration**: New users can register themselves to create accounts.
- **CRUD Operations**: Users can create, read, update, and delete their blogs.
- **Role-based Access Control**: Supports three roles - user, admin, and editor, each with specific permissions.
- **Admin Privileges**: Admins can perform CRUD operations on users, in addition to managing their own blogs.
- **Editor Privileges**: Editors can edit any blog in the system.
- **Image Upload**: Users can upload images for their blogs.
- **Forgot Password Functionality**: Users can reset their passwords via email.
- **Pagination**: Pagination is implemented to show a specific number of blogs per page.
- **Sorting**: Users can sort blogs based on the date they were created.

## Technologies Used

- **Spring Boot JPA**: Provides easy-to-use abstraction for data access using JPA.
- **Thymeleaf**: Server-side template engine for building HTML views.
- **HTML, CSS, JavaScript**: Frontend technologies for building the user interface.
- **Bootstrap 5**: Frontend framework for designing responsive and mobile-first websites.
- **Spring Boot Web**: Provides features for building web applications with Spring Boot.
- **Spring Boot DevTools**: Facilitates faster development with automatic application restarts.
- **H2 Database**: In-memory database for development and testing purposes.
- **Spring Boot Security**: Implements security features like authentication and authorization.
- **Spring Boot Validation**: Supports validation of user inputs.
- **Spring Boot Mail**: Allows sending emails for the forgot password functionality.

## Usage

1. Register for a new account if you are a new user.
2. Log in using your credentials.
3. Create, read, update, or delete your blogs as per your role permissions.
4. Upload images, text, or links for your blogs.
5. Reset your password if you forget it by using the "Forgot Password" functionality.
6. Explore and read other users' blogs even when not logged in.
7. Sort blogs based on the date created.
8. Admins can manage users in addition to managing their own blogs.
9. Editors can edit any blog in the system.

## Contributing

Contributions are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue on GitHub or submit a pull request.


