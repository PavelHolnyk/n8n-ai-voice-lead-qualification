# AI Voice Lead Qualification and Lead Status Monitoring

Portfolio project by Pavlo Holnyk, based on a marketing-agency scenario.

## Overview

A connected n8n automation for website callbacks, AI voice qualification, CRM updates, post-call analysis and management reporting.

## Workflow

Website callback -> Happ.tools voice agent -> Zoho CRM lead creation or update -> OpenAI conversation analysis -> Google Sheets -> daily Telegram report.

The project is divided into four connected n8n workflows. Qualification follows BANT: Budget, Authority, Need and Timeline. Lead correlation uses CRM ID and normalized phone number.

## Stack

Self-hosted n8n, Happ.tools, Zoho CRM API, OpenAI API, Google Sheets API, Telegram Bot API, JavaScript, JSON, webhooks and REST APIs.

## Demo and case study

- [Case study in Notion](https://tangy-whitefish-6d0.notion.site/9c6c12839d06825f8c7d81eca8854cb8)
- [Video demo](https://youtu.be/h6_RmPoplQU)

## Repository contents

Project documentation only. Workflow exports, voice-agent configuration and source files have not been added. Expected conversion improvements are not claimed as measured results.
