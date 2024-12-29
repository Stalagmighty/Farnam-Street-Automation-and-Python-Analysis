README

Text Analysis with Google Sheets and Python

This repository contains a Python script developed as part of my learning journey to explore how to integrate Google Sheets, text analysis, and AI-driven insights. The script is a combination of experiments with Google APIs, text cleaning, word frequency analysis, and OpenAI's GPT for summarising results.

Please note: This script is not a polished, production-ready solution but a learning exercise. Feedback and suggestions are welcome to help improve the code and my understanding.

Features
Google Sheets Integration:

Connects to a Google Sheet using the Google Sheets API.
Reads and processes data from a specified range.
Text Cleaning:

Removes unnecessary characters, whitespace, and Unicode artifacts to ensure the data is clean for analysis.
Word Frequency Analysis:

Counts the frequency of words in the text, excluding common stop words.
Displays the top 20 most common words in the dataset.
Data Visualization:

Generates a bar chart to visualize word frequency using Matplotlib.
AI-Powered Insights:

Uses OpenAI's GPT to provide a natural language summary or interpretation of the most frequent words.
How It Works
Authentication with Google Sheets:

Requires a Google Cloud service account and JSON credentials.
Reads data from a specified sheet and range.
Text Analysis:

Processes content to count word frequencies while excluding common stop words.
Outputs the results as a DataFrame and a bar chart.
AI-Generated Insights:

Prepares a prompt based on the most common words and uses OpenAI GPT to provide a human-readable summary.
Requirements
Python 3.7 or higher
Libraries:
google-auth and google-auth-oauthlib for authentication.
google-api-python-client for accessing Google Sheets.
pandas for data manipulation.
matplotlib for visualizations.
openai for AI integration.
re for text processing.
Setup
Google Sheets API:

Set up a Google Cloud project and enable the Google Sheets API.
Create a service account and download the JSON credentials file.
Share the Google Sheet with the service account email.
Python Environment:

Install the required libraries:
bash
Copy code
pip install google-api-python-client pandas matplotlib openai
Run the Script:

Replace the placeholders in the script:
SERVICE_ACCOUNT_FILE: Path to your JSON credentials.
SPREADSHEET_ID: ID of your Google Sheet.
RANGE_NAME: Range of data to process (e.g., Sheet1!A1:B200).
Run the script in your Python environment.
Useful Documentation
Google Sheets API:

Quickstart Guide
API Reference
OpenAI GPT API:

API Documentation
Python Libraries:

Pandas Documentation
Matplotlib Documentation
Google API Client
Notes
This project reflects my early experiments in integrating these tools.
Expect rough edges and unoptimized code.
Contributions, tips, or best practices are welcome to help refine this project.
Thank you for taking the time to check this out! 😊
