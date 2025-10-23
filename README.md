# Automated-Birthday-Email-Sender
This Python project automatically sends personalized birthday emails to contacts listed in a CSV file.

Features

Reads birthday data from a CSV file (birthdays.csv) containing name, email, month, and day.

Automatically selects a birthday template from multiple options.

Sends personalized emails using SMTP (Gmail).

Can be scheduled to run daily for automated email sending.

How It Works

The script checks if today matches any birthday in the CSV.

If a match is found, it randomly selects a template letter and replaces [NAME] with the recipient's name.

Sends the email securely using Gmail’s SMTP server.

Tech Stack

Python 3

Pandas (for reading and handling CSV data)

SMTP library (for sending emails)

Random module (for template selection)

Datetime module (for date checking)

Data Aspect

Although this project is primarily an automation script, it uses structured data (birthdays.csv) to drive decisions (who gets an email and which template). You could expand this to include:

Analyzing birthday frequency per month.

Predicting optimal send times for higher engagement.

Logging sent emails and analyzing delivery success rates.

Usage

Create a CSV file birthdays.csv with columns: name, email, year, month, day.

Add 2–3 birthday letter templates in the Letters_templates/ folder.

Update MY_EMAIL and PASSWORD with your sender email credentials.

Run the script daily to automatically send birthday wishes.
