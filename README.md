# Government Opportunity Automation with n8n

## Overview
An n8n automation workflow designed to discover government contracting opportunities, filter relevant IT-related bids, classify opportunities using an AI model, and organize results in Google Sheets.

## Project Objectives
- Retrieve government opportunities from the SAM.gov API.
- Parse and process opportunity data.
- Filter opportunities using relevant keywords and eligibility criteria.
- Use an OpenAI model to help classify opportunities.
- Identify and handle duplicate records.
- Store organized results in Google Sheets.

## Workflow Architecture

1. **Scheduled Trigger** — Starts the workflow automatically.
2. **API Integration** — Retrieves government opportunity data.
3. **Data Processing** — Parses responses and extracts relevant fields.
4. **Filtering** — Applies keyword and eligibility criteria.
5. **AI Classification** — Uses an LLM to classify opportunities.
6. **Duplicate Handling** — Helps prevent repeated records.
7. **Google Sheets Integration** — Organizes processed opportunities for review.

## Technologies Used
- n8n
- REST API integration
- SAM.gov API
- OpenAI API / Large Language Models
- JavaScript for data processing
- Google Sheets

## Skills Demonstrated
- Workflow automation and scheduling
- API integration and data extraction
- Data transformation and filtering
- LLM integration
- Conditional logic and duplicate handling
- Automation debugging and workflow design

## Notes
This repository documents the project's general architecture and technical concepts. It does not contain the original company workflow, credentials, private datasets, or internal configuration.

