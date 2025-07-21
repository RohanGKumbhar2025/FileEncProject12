File Enc App
This is a Java application designed to hide and unhide files, secured with an OTP-based authentication system. It utilizes a MySQL database to store user information and hidden file data.

Table of Contents
Project Overview
Features
Technologies Used
Setup and Installation
Prerequisites
Database Setup
Project Configuration
Running the Application
Usage
Project Structure
Contributing
License
Project Overview
The File Enc App provides a secure way for users to hide sensitive files by storing their content in a database and deleting the original file. Users can later retrieve (unhide) these files. Authentication is handled via an OTP (One-Time Password) sent to the user's email address, ensuring secure access to their hidden files.

Features
User Authentication: Secure login and signup using OTP sent to the registered email.
File Hiding: Users can select a file path, and the application will store its content in the database and delete the original file.
File Unhiding: Users can view a list of their hidden files and unhide them, restoring the file to its original path.
Database Integration: Uses MySQL to persist user data and file contents.
Email Service: Integrates with JavaMail API to send OTPs for authentication.
Technologies Used
Java Development Kit (JDK): Version 22
Maven: For dependency management and project build.
MySQL Database: For data storage.
JDBC (Java Database Connectivity): To connect Java application with MySQL.
JavaMail API: For sending emails (OTPs).
Setup and Installation
Prerequisites
Java JDK 22 or higher installed.
Maven installed.
MySQL Server installed and running.
An email account (Gmail recommended) for sending OTPs. You might need to enable "Less secure app access" or generate an App Password for your Gmail account if you encounter authentication issues.
