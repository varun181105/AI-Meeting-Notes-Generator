# AI Meeting Notes Generator (n8n + OpenAI)

## Overview
This project automatically generates meeting notes using AI.  
It receives a meeting transcript through a webhook, summarizes the content using OpenAI, and stores structured notes in Google Sheets.

## Tools Used
- n8n
- OpenAI API
- Webhook Trigger
- Google Sheets

## Workflow
Webhook Transcript → AI Summarization → Save Notes in Google Sheets

## How It Works
1. A meeting transcript is sent to the webhook.
2. The workflow sends the transcript to OpenAI.
3. AI generates a summarized version of the meeting notes.
4. The notes are stored in Google Sheets.

## Setup
1. Import the `workflow.json` file into n8n.
2. Configure OpenAI and Google Sheets credentials.
3. Activate the workflow.

## Note
API keys are not included in this repository for security reasons.
