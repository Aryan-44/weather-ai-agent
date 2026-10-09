# Weather AI Agent 🌦️

An AI-powered weather automation agent built using n8n, Groq, and the Open-Meteo API. It analyzes weather forecasts, generates weather alerts, and sends daily reports through email.

## Features
- Automated daily weather reports
- Weather forecast analysis using an LLM
- Rain probability and temperature alerts
- Automated email notifications
- Scheduled workflow execution using n8n

## Workflow Architecture
1. **Schedule Trigger** — Runs the workflow daily.
2. **HTTP Request** — Retrieves weather forecast data from Open-Meteo.
3. **AI Agent (Groq)** — Analyzes the weather data and generates a readable report.
4. **Gmail** — Sends the weather report and alerts by email.

## Technologies Used
- n8n
- Groq LLM
- Open-Meteo API
- Gmail SMTP
- AI Agent workflows and prompt engineering

## Setup
1. Import `weather-agent-workflow.json` into n8n.
2. Configure your Groq model credentials.
3. Configure your Gmail credentials.
4. Set the appropriate timezone and schedule.
5. Execute the workflow and verify email delivery.

## Security
Configure credentials securely in n8n. Never publish API keys, passwords, or personal credentials.

## Author
GitHub: https://github.com/Aryan-44

## Workflow Screenshot

![Weather AI Agent Workflow](weather-agent-workflow.png)
