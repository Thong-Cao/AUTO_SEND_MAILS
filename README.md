# Automated Email Sender

## Overview
This project contains a Jupyter Notebook that automates the process of sending emails. It is designed to handle both plain text and multipart messages, which can include attachments.

## Features
- **Email Sending**: Utilizes the `smtplib` library to connect to mail servers and send emails.
- **Attachments**: Supports adding attachments to emails using `MIMEBase`.
- **Data Handling**: Integrates with `pandas` for handling recipient data, potentially reading from external sources like CSV files.
