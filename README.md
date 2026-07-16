# AI Email Assistant

## Overview
This n8n workflow automatically:
- Reads unread Gmail messages.
- Uses the Groq API to summarize emails.
- Extracts action items, deadlines, and priority.
- Sends the summary back by email.

## Technologies
- n8n
- Gmail API
- Groq API
- Llama 3.3 70B

## Setup
1. Import the workflow into n8n.
2. Connect your Gmail credentials.
3. Add your own Groq API key.
4. Run the workflow.

 ## Screenshots

### n8n Workflow
![Workflow](Screenshots/Screenshot%20(41).png)

### Email Summary Output
![Email Summary](Screenshots/Screenshot%20(42).png)

## Project Structure

- `README.md` – Project documentation
- `ai-email-assistant.json` – n8n workflow
- `Screenshots/` – Workflow and output images

## Author
Sonia Kanwal
