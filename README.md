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

<h2>Contributors</h2>
<dl>
<dd>Satya Prakash Sahoo</dd>
<dd><a href="Satyaprakash.od@gmail.com">Satyaprakash.od@gmail.com</a></dd>
</dl>

<h2>Contributing</h2>

<p>
    Contributions are welcome! Fork the repository, make your changes, and submit a pull request.
</p>

