# Email_via_python-regexp-

## Profile Details Form with Email Notification

This Python script collects user details such as name, date of birth, phone number, Instagram ID, and email, then validates the input using regular expressions. Once validated, the script sends an email with the provided details using the Gmail SMTP server.

## Features

Validates user input for name, date of birth, phone number, and email.

Sends an email containing the collected details.

Uses the smtplib library for sending emails.

Implements error handling for email delivery failures.

## Prerequisites

Ensure you have the following installed:

Python 3.x

Required libraries:
               pip install re smtplib email

## Input Validation

Name: Only letters and spaces are allowed.

Date of Birth: Must be in DD-MM-YYYY format.

Phone Number: Must start with 6, 7, 8, or 9 and follow the XXX-XXX-XXXX pattern.

Email: Must be a valid Gmail address.

## Email Configuration

Update the msg['From'] and server.login() credentials with your own Gmail account.

Enable Less Secure Apps in your Google account or generate an App Password for better security.
