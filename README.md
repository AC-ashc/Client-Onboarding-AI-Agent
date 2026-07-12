# Client-Onboarding-AI-Agent
AI Powered Client Onboarding Agent

# Overview
AI-Powered Client Onboarding Agent that automates the client onboarding process from start to finish. Clients submit their information through a digital onboarding form, and the agent intelligently processes the details, stores the data in Google Sheets, and automatically sends a personalized welcome and onboarding email. This solution streamlines client intake, reduces manual effort, ensures accurate record-keeping, and delivers a seamless onboarding experience.


# Workflow
Form Submission
       │
       ├──────────────► AI Agent (Email Generator)
       │                     │
       │                     ├─ Gemini Chat Model
       │                     ├─ Structured Output Parser
       │                     ▼
       │              Send Gmail Message
       │
       └──────────────► AI Agent (Data Extractor)
                             │
                             ├─ Gemini Chat Model
                             ├─ Structured Output Parser
                             ▼
                      Append Row to Google Sheet

# Techstack
* n8n
* Gemini model API
* AI agent
* Google sheet 
* Gmail
* API calls
* JSON
* OAuth
* Webhook

## Screenshots

See the screenshots folder for workflow examples.

## Importing the Workflow

1. Download the JSON file.
2. Open n8n.
3. Click Import Workflow.
4. Upload the JSON file.

⚠️ Disclaimer

This repository is a personal educational project built for learning and portfolio purposes only. This workflow is provided as-is and is not intended for production use without further testing, validation, and security review. The author is not affiliated with n8n or Google. API usage is subject to each provider's own terms of service and pricing. As this workflow processes client information, do not use it with real client data, PII, or sensitive information without appropriate data handling, privacy compliance measures, and applicable regulatory requirements (PIPEDA, GDPR) in place. The author accepts no liability for any outcomes arising from the use of this workflow.

## Author

AC
