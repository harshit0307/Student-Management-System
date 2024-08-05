
<body>

<h1>Student Management System</h1>

<h2>Overview</h2>
<p>The <strong>Student Management System</strong> is a console-based application developed in C++ designed to manage student records efficiently. It includes features for adding, viewing, updating, and deleting student information, as well as secure user authentication through login and signup.</p>

<h2>Features</h2>
<ul>
    <li><strong>User Authentication</strong>: Secure login and signup functionality with encryption.</li>
    <li><strong>CRUD Operations</strong>: Create, Read, Update, and Delete student records.</li>
    <li><strong>Data Persistence</strong>: Utilizes file handling for storing and retrieving student data.</li>
    <li><strong>Console Interface</strong>: User-friendly console interface for interaction.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Programming Language</strong>: C++</li>
    <li><strong>Concepts</strong>:</li>
    <ul>
        <li>Object-Oriented Programming (OOP)</li>
        <li>Data Structures</li>
        <li>Input/Output Streams</li>
        <li>Memory Management</li>
        <li>Standard Template Library (STL)</li>
    </ul>
</ul>

<h2>Installation</h2>
<ol>
    <li><strong>Clone the Repository</strong>:
        <pre><code>git clone https://github.com/yourusername/Student-Management-System.git
cd Student-Management-System
</code></pre>
    </li>
    <li><strong>Compile the Code</strong>:
        <pre><code>g++ -o student_management_system main.cpp
</code></pre>
    </li>
    <li><strong>Run the Application</strong>:
        <pre><code>./student_management_system
</code></pre>
    </li>
</ol>

<h2>Usage</h2>
<ol>
    <li><strong>Sign Up</strong>: Create a new user account.</li>
    <li><strong>Log In</strong>: Access the system using your credentials.</li>
    <li><strong>Manage Records</strong>:
        <ul>
            <li>Add new student records.</li>
            <li>View existing records.</li>
            <li>Update student information.</li>
            <li>Delete student records.</li>
        </ul>
    </li>
</ol>

<h2>Project Structure</h2>
<pre><code>Student-Management-System/
├── main.cpp            # Main entry point of the application
├── adminFunction.h     # Header file for Admin class
├── Loading.h           # Header file for loading ui
├── resources/          # Directory for storing student data files
│   └── data.csv        # File for storing student records
└── README.md           # Project README file
</code></pre>

</body>
</html>
