# College Management System - Laravel

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
- [Satyaprakash.od@gmail.com](Satyaprakash.od@gmail.com)

Feel free to contribute by forking the repository and submitting pull requests.

