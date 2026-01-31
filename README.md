# E-Learning Platform

A comprehensive, lightweight E-Learning Platform built with PHP and MySQL. This application is designed to facilitate online education by managing resources, courses, class schedules, and user roles.

## 🚀 Features

- **User Authentication**: Secure login and registration system with password hashing.
- **Role-Based Access Control**: Manage different user roles (e.g., Admin, Instructor, Student).
- **Resource Library**: Access and manage educational materials such as books, videos, and PDFs.
- **Course Management**: Create and track courses, including instructor details and course status (Active, Completed, Upcoming).
- **Class Schedule**: Organize class timetables with dates, times, and topics.
- **Responsive Design**: User-friendly interface accessible on various devices.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP (Vanilla)
- **Database**: MySQL
- **Server Environment**: Compatible with XAMPP, WAMP, LAMP, or any standard PHP/MySQL environment.

## 📂 Project Structure

```
elearning/
├── css/
│   └── styles.css          # Application styling
├── database/
│   └── elearning_platform.sql # Database schema and initial data
├── js/
│   └── scripts.js          # Client-side interactivity
├── php/
│   ├── db.php              # Database connection and helper functions
│   ├── login.php           # User login logic
│   ├── logout.php          # Session termination
│   ├── register.php        # New user registration
│   ├── courses.php         # Course management logic
│   ├── resources.php       # Resource library logic
│   ├── roles.php           # User role management
│   └── schedule.php        # Class scheduling logic
├── index.php               # Main entry point / Landing page
└── mini.pdf                # Sample resource file
```

## ⚙️ Setup & Installation

1.  **Clone or Download**:
    -   Download the project files and place them in your web server's document root (e.g., `htdocs` for XAMPP).

2.  **Database Setup**:
    -   Open your MySQL administration tool (e.g., phpMyAdmin).
    -   Create a new database or simply import the provided SQL file.
    -   Import `database/elearning_platform.sql`. This will create the database `elearning_platform`, necessary tables, and a default admin user.

3.  **Configuration**:
    -   Open `php/db.php`.
    -   Update the `$servername`, `$username`, `$password`, and `$dbname` variables if your database configuration differs from the defaults:
        ```php
        $servername = "localhost";
        $username = "root";
        $password = "";
        $dbname = "elearning_platform";
        ```

4.  **Run the Application**:
    -   Start your Apache and MySQL servers.
    -   Open your web browser and navigate to:
        `http://localhost/elearning` (or the path where you placed the project).

## 🔑 Default Credentials

The database script comes with a pre-configured admin account:

-   **Username**: `admin`
-   **Password**: `admin123`

## 📝 Usage

-   **Home**: Overview of the platform and navigation.
-   **Register/Login**: Create an account or log in to access restricted features.
-   **Resources**: Browse available learning materials.
-   **Courses**: View and manage course listings.
-   **Schedule**: Check upcoming classes.
-   **User Management**: (Admin) Manage user roles and permissions.

## 📄 License

This project is open-source and available for educational purposes.
