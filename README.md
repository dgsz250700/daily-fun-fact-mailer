# Daily Report Emailer

An automated email workflow built with n8n, OpenAI, Gmail, and financial data APIs.

## Overview
This project sends a daily finance report by email. It uses an n8n workflow to fetch financial information, process or summarize it with OpenAI, and deliver the final report through Gmail.

## Workflow
Schedule Trigger → Financial Data API → OpenAI → Gmail

## Tech Stack
- n8n
- OpenAI
- Gmail
- Alpha Vantage
- Marketaux

## Project Files
- `workflow 1.2.json` – exported n8n workflow
- `README.md` – project documentation
- `.gitignore` – ignored files configuration

## Setup
1. Import the workflow JSON into n8n.
2. Configure your OpenAI credentials.
3. Configure your Gmail credentials.
4. Add the required API credentials for the financial data source.
5. Enable the workflow.

## Security
No credentials, API keys, or private configuration values are included in this repository.
