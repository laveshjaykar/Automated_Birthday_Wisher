# Automated Birthday Wisher

This project is an automated system designed to send out personalized birthday wishes. It leverages Python's powerful libraries to check for birthdays from a provided dataset and sends customized birthday greetings via email.

Features

Daily Birthday Check: Automatically checks the current date against a dataset of birthdays.
Personalized Greetings: Selects a random greeting template and personalizes it with the recipient's name.
Email Integration: Sends the personalized birthday wish via email using SMTP protocol.
How It Works

Date Checking: Utilizes Python's datetime library to obtain the current date.
Data Management: Employs pandas to read and manage birthday data from a CSV file.
Random Selection: Uses Python's random module to select a random greeting template.
Email Sending: Implements Python's smtplib for email sending functionality.
Environment Variables: Leverages os.environ to securely access email credentials stored in environment variables.
