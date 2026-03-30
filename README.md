DEMO LINK - https://nathiyabhuvanes-pixel.github.io/validate/validate.html

PPT LINK - https://docs.google.com/presentation/d/1LdyRRws1IC5Xry3mAI41QvBze1DYY0hG/edit?usp=sharing&ouid=109054685003067466524&rtpof=true&sd=true

Form Validation Project

Overview

This project is a simple Form Validation System built using HTML, CSS, and JavaScript. It validates user input before submitting the form to ensure correct and complete data.

Objective

To check user inputs before form submission
To prevent invalid or incomplete data
To improve user experience with instant feedback

Technologies Used

HTML – For structure
CSS – For styling
JavaScript – For validation logic

Features

User-friendly registration form
Real-time validation using JavaScript
Displays alert messages for errors
Prevents form submission if inputs are invalid

Form Fields

Name
Email
Password
Phone Number

Validation Rules

Name → Cannot be empty
Email → Must follow proper email format
Password → Minimum 6 characters
Phone Number → Must be exactly 10 digits

How It Works

User fills the form
On clicking Submit, validateForm() function is triggered
JavaScript checks each input:
If any field is invalid → Shows alert message
If all fields are valid → Form submitted successfully

Validation Logic

Uses Regular Expressions (Regex) for:
Email validation
Phone number validation
Uses conditional statements to check:
Empty fields
Password length

How to Run

Copy the code into a file
Save it as index.html
Open it in any web browser
Fill the form and test validation

Example Alerts

"Name cannot be empty"
"Enter valid Email"
"Password must be at least 6 characters"
"Enter valid 10-digit phone number"
"Form Submitted Successfully"

Future Improvements

Add error messages below input fields (instead of alerts)
Use advanced email validation
Add password strength indicator
Connect form to backend database
