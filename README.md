# Automated Weekly Sales Report — n8n Workflow

## What It Does
Runs every Monday at 8am, reads sales data from Google Sheets, 
calculates weekly totals, and sends a formatted summary report 
to Telegram automatically.

## Workflow
Schedule Trigger → Google Sheets → Code Node → Telegram

## Tech Stack
- n8n
- Google Sheets
- Telegram Bot API

## Features
- Total revenue calculation
- Units sold summary
- Per-salesperson leaderboard
- Fully automated, zero manual work

## Setup
1. Import the workflow JSON into your n8n instance
2. Connect your Google Sheets credential
3. Connect your Telegram Bot credential
4. Update the Sheet ID in the Google Sheets node
5. Activate the workflow

## Use Case
Small business owners who want automatic weekly 
performance reports without manual data compilation.

## Result
- 45 minutes of manual work eliminated per week
- Report delivered every Monday at 8am without fail
