# Meeting Minutes Automation

I built this n8n workflow to turn meeting notes into a clear summary and organized action items, then send the results by email and save the tasks for follow-up.

## How it works

1. The user submits the meeting title, meeting notes, and email address through a form.
2. Claude reads the notes and extracts a short meeting summary and action items, including the task owner and due date when available.
3. The workflow separates the extracted tasks into individual items.
4. The tasks are saved to Google Sheets with a Pending status.
5. The meeting summary is sent to the submitted email address.

## Main features

- Meeting notes processing through a form.
- AI-generated meeting summary.
- Action item extraction with owners and due dates when available.
- Automatic task logging in Google Sheets.
- Email delivery of the meeting summary.

## Technologies

n8n, Anthropic Claude, Google Sheets, Gmail, JavaScript, and n8n Forms.

## Setup

Import [workflow.json](./workflow.json) into n8n, configure your Anthropic, Google Sheets, and Gmail credentials, then connect your task-tracking sheet and test the form with sample meeting notes.
