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

### 1. n8n Workflow - Part 1
![Workflow Part 1](Screenshots/Screenshot(41).png)

### 2. n8n Workflow - Part 2
![Workflow Part 2](Screenshots/Screenshot(42).png)

### 3. AI Email Summary Output - WhatsApp
![Email Output](Screenshots/whatsapp%20Image%202026-07-11%20at....jpeg)

## Project Structure

- `README.md` – Project documentation
- `ai-email-assistant.json` – n8n workflow
- `Screenshots/` – Workflow and output images

## Author
Sonia Kanwal
