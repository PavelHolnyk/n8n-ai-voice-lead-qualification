# AI Voice Lead Qualification & CRM Follow-up

**n8n · Happ.tools · Zoho CRM · OpenAI · Google Sheets · Telegram**

A website callback becomes a personalized AI voice conversation, BANT qualification, CRM updates and a daily management report.

Portfolio project based on the Investimant&Co marketing-agency scenario.

## Problem

Callback requests, CRM matching, qualification and post-call review were disconnected manual steps. Managers also had to copy call findings into spreadsheets and assemble funnel reports. Matching only by phone number risked attaching a conversation to the wrong Lead.

## Solution

Four connected n8n workflows cover callback intake, CRM creation or update, post-call analysis and scheduled reporting.

Website callback → Happ.tools voice call → Zoho CRM → OpenAI conversation analysis → Google Sheets → Telegram report.

- Qualify leads using **BANT: Budget, Authority, Need and Timeline**.
- Use existing CRM details to personalize the call.
- Match completed conversations using **CRM Lead ID + normalized phone**.
- Store structured call analysis before marking a Lead as processed.
- Combine lead statuses and conversation insights in one management report.

## Results

- **Automatic first-pass qualification:** the AI voice agent collects qualification details and updates CRM records, reducing routine work for managers.
- **Consistent BANT scoring:** leads receive structured qualification data to support follow-up prioritization.
- **Conversation insights:** completed dialogues are analyzed for customer needs, objections, agent mistakes and successful communication patterns.
- **Daily management reporting:** a consolidated Telegram report is scheduled for **17:00**, combining current Lead statuses and call insights.
- **Expected conversion impact:** the Notion case projects **2.5× growth in conversion from the initial call to a closed deal** through faster response and data-driven follow-up. This is an expected outcome, not a verified measured increase.

## Tech Stack

Self-hosted n8n, Happ.tools Voice Agent, Zoho CRM API, OpenAI API, Google Sheets API, Telegram Bot API, JavaScript Code nodes, JSON, Structured Output Parser, webhooks and REST APIs.

## Demo & Case Study

- [Watch the demo](https://youtu.be/h6_RmPoplQU)
- [Read the full Notion case](https://tangy-whitefish-6d0.notion.site/9c6c12839d06825f8c7d81eca8854cb8)

## Author

**Pavlo Holnyk — AI Automation & AI Agents**

[Portfolio](https://tangy-whitefish-6d0.notion.site/408c12839d06816f9e61ff1aa7392587) · [LinkedIn](https://www.linkedin.com/in/pavlo-holnyk/) · [Upwork](https://www.upwork.com/freelancers/~011ee82fd5725aa92e)
