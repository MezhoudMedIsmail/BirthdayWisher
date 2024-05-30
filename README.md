
*Automated Birthday Wishes App*

This application automates the process of sending personalized birthday wishes to individuals whose birthdays are saved in a CSV file. Utilizing Python, the app checks the current date, identifies any birthdays that match today's date, and sends a customized birthday email to the celebrants. The email content is dynamically generated from pre-written templates, ensuring each message feels personal and unique. The app leverages the `smtplib` library for email delivery and ensures secure connection through Gmail's SMTP server. Here’s a quick overview of the process:

1. **Read and Parse CSV**: The app reads a CSV file containing birthday data, including names, emails, and birth dates.
2. **Check Today’s Birthdays**: It checks if the current date matches any birthday in the CSV.
3. **Generate Email Content**: If a match is found, it selects a random birthday template, replaces placeholders with the person's name, and prepares the email content.
4. **Send Email**: The app securely logs into a Gmail account using SMTP, then sends the personalized birthday email to the recipient.

