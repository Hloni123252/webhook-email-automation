# Webhook to Email Automation

A Python automation project that processes JSON webhook payloads and sends real-time email alerts via Gmail SMTP API.

## What It Does

- Simulates webhook payloads (new customer signups, cancellations)
- Processes JSON data and extracts key information
- Applies conditional logic (e.g., HIGH priority for premium users)
- Sends formatted email alerts using Gmail SMTP API
- Includes error handling for failed email delivery

## Tech Stack

- Python
- Jupyter Notebook
- SMTP (Gmail API)

## How to Run

1. Clone this repository
2. Open `webhook-email-automation.ipynb` in Jupyter or VS Code
3. Add your own Gmail App Password (see note below)
4. Run the cells in order

## Important Security Note

⚠️ This code uses a placeholder for the Gmail App Password. You must generate your own at [Google App Passwords](https://myaccount.google.com/apppasswords) and add it to the code. Never commit real passwords to GitHub.

## Example Output
