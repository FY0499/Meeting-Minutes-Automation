# Meeting Minutes Automation

An n8n workflow that turns meeting notes into a structured summary and action-item list, then emails the result to a recipient.

## How it works

1. A user submits a meeting title, notes, and an email address through an n8n form.
2. An AI model processes the submitted meeting notes and returns a summary and tasks.
3. A JavaScript step parses the model response and adds the meeting title and recipient email.
4. The workflow delivers the meeting output by email.

## Technologies

- n8n
- AI model integration
- JavaScript
- Gmail
- n8n Forms

## Setup

1. Import workflow.json into n8n.
2. Configure the required AI, Google Sheets (if used in your instance), and Gmail credentials.
3. Review the form fields and recipient handling, then test with sample meeting notes.

## Notes

This repository contains the exported n8n workflow. Configure your own credentials and integrations in n8n before running it.
