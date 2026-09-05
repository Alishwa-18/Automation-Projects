# AI Automation Projects

This repository contains automation workflows I have built using **n8n**, **Make.com**, AI models, APIs, and business platforms.

The projects cover AI agents, meeting management, reminders, CRM processes, customer communication, invoice processing, and payment workflows.

## Main Areas
### AI Agents
Agent-based workflows that understand user requests, choose the correct action, and connect with other workflows or business tools.

Examples include:
* Master Agent
* Appointment Agent
* Reminder Agent
* Telegram Task Creation Agent

### Meetings and Reminders
Workflows for managing meetings, calendar events, task reminders, recurring reminders, cancellations, rescheduling, and snoozed notifications.

These workflows connect tools such as:
* Google Calendar
* Microsoft Outlook
* Notion
* Telegram

### CRM and Customer Communication
Automations for handling customer requests, managing CRM data, scheduling appointments, and sending updates across different communication channels.

This area includes integrations with:
* HubSpot
* Zoho CRM
* Zoho Books
* WooCommerce
* Gmail
* Twilio
* WhatsApp
* Google Sheets
* Supabase

### Invoice and Payment Automation
Workflows that process invoices, extract information from documents, update records, notify vendors, and manage payment-related tasks.

These projects use tools such as:
* Gmail
* Google Drive
* Google Sheets
* Airtable
* Wise
* PDF.co
* OpenAI

## Featured Workflows

### Master Agent
A multi-agent workflow that receives a request and routes it to the correct specialized workflow. It uses an AI agent, conversation memory, tool workflows, Telegram, and error handling.

### HubSpot Chatbot
A customer communication workflow connected with HubSpot, Twilio, Google Sheets, and OpenAI. It manages incoming requests and supports automated follow-ups.

### Meeting Management System
A group of connected workflows for creating meetings, separating personal and project meetings, handling cancellations or rescheduling, and sending reminders.

### Invoice Processing
An automated invoice workflow that receives documents through Gmail, extracts invoice data, stores files, updates business records, and handles different processing conditions.

### Wise Invoice and Vendor Workflows
Automations for processing invoice information, updating payment records, and notifying vendors about payment status.

### CRM and WooCommerce Automation
A Make.com workflow that classifies incoming requests and connects with Zoho CRM, Zoho Books, WooCommerce, Gmail, and OpenAI.

## Platforms and Technologies
* n8n
* Make.com
* OpenAI
* LangChain nodes
* JavaScript and Python
* REST APIs and webhooks
* Google Workspace
* Microsoft Outlook
* Notion
* Telegram
* WhatsApp and Twilio
* HubSpot
* Zoho CRM and Zoho Books
* WooCommerce
* Airtable
* Supabase
* Wise

## Using the Workflows

### n8n
1. Download the required `.json` workflow.
2. Open your n8n workspace.
3. Select **Import from File**.
4. Add your own credentials.
5. Review the nodes and environment-specific values before running the workflow.

### Make.com
1. Download one of the `.json.json` blueprint files.
2. Open a scenario in Make.com.
3. Import the blueprint.
4. Connect your own accounts and replace any environment-specific values.
5. Test the scenario before activating it.

## Security
The exported workflows do not include working account access after import. You must configure your own credentials, webhook URLs, database identifiers, and API settings.

Never commit active API keys, passwords, access tokens, client secrets, or private customer information to a public repository.

## About Me
I am **Alishwa Shakeel**, an AI Automation Engineer focused on agentic workflows, LLM agents, API integrations, and business process automation.

* [GitHub](https://github.com/Alishwa-18)
* [LinkedIn](https://www.linkedin.com/in/alishwa-shakeel-127959269)
