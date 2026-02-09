## AI-Enhanced Lead Routing & Scoring Automation

Make.com, HubSpot CRM, AI Prompting, Google Sheets, Slack, Outlook
GitHub: https://github.com/JavierZavaleta94

## Overview

This project demonstrates an AI-powered go-to-market workflow that automates lead scoring, prioritization, and routing across multiple platforms. It captures inbound leads, enriches the data using AI, and ensures rapid actionable follow-up to improve revenue pipeline efficiency.

## Key Features

- AI-Driven Lead Scoring: Generates lead_score, qualification (Hot/Warm/Cold), next_action, AI confidence, and insight_summary based on HubSpot form submissions.
- CRM Integration: Updates HubSpot contact records with AI-enriched information.
- Notifications & Routing: Sends Outlook emails and Slack DMs for HOT leads.
- Tracking & Reporting: Logs all lead events and AI outputs in Google Sheets.
- End-to-End Automation: Integrates AI into multi-platform workflows to improve lead triage and pipeline visibility.

## How It Works

1. User submits a HubSpot form embedded on a static HTML page.
2. Lead data is analyzed by AI using a structured prompt.
3. AI output updates the HubSpot contact.
4. Outlook email notification is sent for every new lead.
5. Lead data is logged in Google Sheets for reporting.
6. HOT leads trigger Slack direct messages to the lead owner.

## Use Cases

- Sales & Marketing Teams: Quickly identify high-value leads and prioritize follow-up.
- Revenue Ops / GTM Automation: Reduce manual triage and accelerate lead-to-action speed.
- AI Workflow Demo: Showcases practical integration of AI with low-code automation platforms.

## Getting Started

Clone the repository:

git clone https://github.com/JavierZavaleta94/ai-lead-routing.git


1. Configure HubSpot form embed on your HTML page. https://javierzavaleta94.github.io/AI-Enhanced-Lead-Routing-Scoring-Automation/
2. Set up Make.com scenario with modules for:
3. HubSpot form capture

- AI prompt (Make AI toolkit)
- CRM updates
- Outlook email notifications
- Google Sheets logging https://docs.google.com/spreadsheets/d/14dLw_6fhCe7Xw9jM_ucHWLITzXCvCYpVdReaWtCttKM/edit?usp=sharing
- Slack notifications for HOT leads

4. Adjust AI prompts to match lead scoring criteria.
5. Test workflow with sample leads.

## Project Highlights

- Demonstrates AI + GTM automation in a real-world workflow.
- Integrates multi-platform automation across CRM, email, collaboration, and reporting tools.
- Provides observable metrics for lead prioritization and response tracking.