General Description of the Project

This project is a web application developed in PHP, allowing users to sign up, log in, and complete a customized profile. The application was built to demonstrate the integration of two different databases: MySQL and MongoDB. MySQL is used for managing essential data (such as login credentials), while MongoDB is used to store and manage more complex user information, such as their customized profile.

Main Features Implemented
Sign-Up System:

Users can create an account by providing an email address and a password.
Data validation: Ensures completeness and correctness (e.g., email format verification).
Data is stored in a MySQL database for quick access.

Login System:

Users can log in using their email and password.
Implements input verification to ensure credentials are correct.
Session management maintains user connection during their session.

User Profile (Registration/Profile):

After logging in, users can complete and edit a customized profile.
Fields included: age, job, and other personal data, which are stored in MongoDB for flexibility.
Allows users to view or update their information dynamically.

Database Architecture:

MySQL for authentication and user management.
MongoDB for storing additional user profile data.

Data Security:
Password hashing.Server-side data validation to prevent malicious input.
Features and Technologies Used

Technologies:

Backend: PHP
Databases: MySQL, MongoDB
Frontend: HTML, CSS, JavaScript.

Libraries Used:
PDO for MySQL.
PHP extension for MongoDB.

Potential Future Improvements:

Implementing a modern UI framework, such as Tailwind.

Database Optimization:Indexing frequently queried fields for faster performance.
