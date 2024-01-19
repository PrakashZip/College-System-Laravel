<h1>College Management System</h1>

<p>
    This College Management System project, developed using Laravel and MySQL, is designed to streamline various tasks
    for students, teachers, and administrators.
</p>

<h2>Features</h2>

<ul>
    <li>Student Portal:
        <ul>
            <li>View Marksheet</li>
            <li>Access Class Schedule</li>
        </ul>
    </li>
    <li>Teacher Portal:
        <ul>
            <li>Add Students</li>
            <li>Commit Attendance</li>
        </ul>
    </li>
    <li>Admin Portal:
        <ul>
            <li>Add, Delete, and Edit Teachers</li>
            <li>Add, Delete, and Edit Students</li>
            <li>Add, Delete, and Edit Parents</li>
        </ul>
    </li>
</ul>

<h2>How to Run Locally</h2>

<ol>
    <li>Clone the Repository:
        <pre>git clone https://github.com/PrakashZip/College-System-Laravel.git</pre>
    </li>
    <li>Install Dependencies:
        <pre>composer install</pre>
    </li>
    <li>Set Up Database:
        <ul>
            <li>Copy <code>.env.example</code> to <code>.env</code> and configure your database settings.</li>
            <li>Run migrations: <code>php artisan migrate</code></li>
        </ul>
    </li>
    <li>Generate Application Key:
        <pre>php artisan key:generate</pre>
    </li>
    <li>Run the Development Server:
        <pre>php artisan serve</pre>
    </li>
</ol>

<h2>Practical Use Case</h2>

<p>
    This system is ideal for educational institutions to efficiently manage student information, attendance, and
    academic records. It provides a user-friendly interface for students, teachers, and administrators to perform their
    respective tasks seamlessly.
</p>

<h2>Login Credentials</h2>

<dl>
    <dt>Admin:</dt>
    <dd>Email: admin@gmail.com | Password: admin123</dd>
    <dt>Teacher:</dt>
    <dd>Email: teacher@gmail.com | Password: teacher123</dd>
    <dt>Parent:</dt>
    <dd>Email: parent@gmail.com | Password: parent123</dd>
    <dt>Student:</dt>
    <dd>Email: student@gmail.com | Password: student123</dd>
</dl>

<h2>Exceptions</h2>

<p>
    While the application is designed with robust input validation and error handling, unexpected inputs or system
    configurations may lead to exceptions. Please ensure correct configurations and report any issues on the project
    repository.
</p>

<h2>Contributing</h2>

<p>
    Contributions are welcome! Fork the repository, make your changes, and submit a pull request.
</p>






# College Management System - Laravel - [@prakashZip](https://github.com/prakashZip)

## Overview

This College Management System is a Laravel-based web application designed to streamline various administrative tasks in a college environment. Students, teachers, and parents can log in to access relevant information, and administrators have control over user management.

## Features

### For Admin:

- **Manage Users:**
  - Add, delete, and edit teachers, students, and parents.

### For Teacher:

- **Student Management:**
  - Add students to the system.
  - Commit attendance for classes.

- **Subject and Class Management:**
  - Manage subjects and classes assigned to the teacher.

### For Student:

- **Mark Sheet:**
  - View personal mark sheets.

- **Class Schedule:**
  - Access class schedules.

### For Parent:

- **Student Information:**
  - View information about their child's academic progress.

## How to Run on Your Local Machine

1. **Requirements:**
   - PHP and Composer installed on your machine.
   - MySQL database.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/PrakashZip/College-System-Laravel.git
   cd College-System-Laravel
   ```

3. **Install Dependencies:**
   ```bash
   composer install
   ```

4. **Configure Environment:**
   - Duplicate the `.env.example` file and rename it to `.env`.
   - Configure your database settings.

5. **Generate Application Key:**
   ```bash
   php artisan key:generate
   ```

6. **Run Migrations and Seeders:**
   ```bash
   php artisan migrate --seed
   ```

7. **Serve the Application:**
   ```bash
   php artisan serve
   ```

8. **Access the Application:**
   - Open your browser and go to `http://127.0.0.1:8000`.

9. **Login Credentials:**
   - Admin: email = admin@gmail.com, password = admin123
   - Teacher: email = teacher@gmail.com, password = teacher123
   - Parent: email = parent@gmail.com, password = parent123
   - Student: email = student@gmail.com, password = student123

## Practical Use Case

This College Management System is designed for educational institutions to efficiently manage student information, attendance, and academic records. It provides a centralized platform for students, teachers, parents, and administrators to access and manage relevant data.

## Exceptions

- Input validations are implemented, but incorrect inputs may still cause unexpected behavior. Ensure correct inputs during interactions.

- Exception handling is designed to cover common scenarios, but additional testing and improvements may be needed.

## Contributors

- Satya Prakash Sahoo
- [Satyaprakash.od@gmail.com](mailto:Satyaprakash.od@gmail.com)

Feel free to contribute by forking the repository and submitting pull requests.

