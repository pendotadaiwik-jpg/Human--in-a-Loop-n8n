# Human-in-the-Loop AI Email Automation

## Overview
This project automates email drafting using AI while keeping a human in control of the final sending decision.

Built with **n8n, Google Gemini, Gmail, and Google Sheets**, the workflow generates email drafts, requests human approval, and sends approved emails.

## Workflow
1. **Form Submission:** Collects the email request through an n8n form.
2. **Data Storage:** Records the request in Google Sheets.
3. **AI Email Generation:** Uses Google Gemini to generate an email draft.
4. **Human Approval:** Sends the draft for review before sending.
5. **Decision Handling:** Classifies the response as approved or denied.
6. **Email Delivery:** Sends the approved email or generates a revised draft if changes are needed.

## Technologies Used
- n8n — workflow automation
- Google Gemini — AI-powered email generation
- Gmail — email review and delivery
- Google Sheets — data storage

## Key Features
- Human approval before email delivery
- AI-generated email drafts
- Automated workflow branching
- Google Sheets integration
- Email revision when approval is denied

## Project Status
Portfolio project. Credentials and integrations must be configured in n8n before running the workflow.

## Security Note
The workflow export shared in this repository is sanitized. Configure your own credentials and resource IDs before importing and running it.
