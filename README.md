# Ai-Automation-projects 
# AI-Powered Email Automation Agent (n8n + Google Contacts + Gemini API)

This project automates personalized email communication using n8n, Google Contacts, and Gemini API.
The workflow finds customer emails, generates customized messages, and sends them after a human review step.

# Features
Automatically fetches customer emails from Google Contacts using only the name
Generates personalized email content using Gemini API
Human review/approval step before sending
Sends follow-up, reminder, and update emails
Works for both customer communication and team communication
Reduces manual typing and saves time

# Technology Stack
n8n (workflow automation)
Google Contacts API
Gmail API
Gemini API (AI text generation)
Human-in-the-loop step

# Required Credentials (User Must Add Their Own)
This project needs two credentials.
Users must add their own credentials inside n8n.

# 1. Gmail Credentials
Used for:
Accessing Google Contacts
Fetching email addresses
Sending emails via Gmail
Users must add:
Google OAuth / Gmail API Credential in n8n

# 2. Gemini API Key
Used for:
Generating personalized email content
AI-written message drafts
Users must add:
Gemini API Key (from Google AI Studio)

# Important:
This project does not include any credentials.
Users must:
Add their own keys safely
Never upload keys or secrets to GitHub

# How It Works:
User enters the customer name
The agent finds the email through Google Contacts
Gemini generates a personalized message
User reviews and approves
Email is sent automatically

# Demo Video
A short demo video is included in this repository showing the full workflow.

https://drive.google.com/file/d/1Ztc0EZe7KMZgSRKzL1tegW9oMRgAgbZx/view?usp=drive_link

