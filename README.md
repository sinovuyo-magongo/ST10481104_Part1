# Chat App Part 1 – Login System
Overview

This project implements a basic user registration and login system in Java. It validates user details such as username, password complexity, and South African phone numbers before allowing registration and login.

## Features
Username Validation
Must contain an underscore (_)
Must not exceed 8 characters
Password Complexity Check

## Password must include:

At least 8 characters
At least one uppercase letter
At least one number
At least one special character

## Phone Number Validation
Must start with South Africa’s international code: +27
Must be exactly 12 characters long
User Registration
Validates all inputs before saving user details
Returns appropriate error messages if validation fails

## User Login
Checks entered username and password against stored values
Login Status Feedback
Displays a welcome message on successful login
Displays an error message on failure
Class Structure
Login.java
Methods:
Method	Description
checkUserName(String username)	Validates username format
checkPasswordComplexity(String password)	Validates password strength
checkCellPhoneNumber(String phone)	Validates SA phone number
registerUser(String username, String password, String phoneNumber)	Registers a user
loginUser(String username, String password)	Authenticates user
returnLoginStatus(boolean success)	Returns login message
