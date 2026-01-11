# AI Workflow – Inbox Triage (n8n Demo)

## Overview
This is a demo project showing how **n8n + AI can automate internal task handling** for small teams.

It demonstrates a realistic workflow where incoming requests are:
- Received via webhook
- Classified using an AI (OpenAI) node
- Parsed into structured JSON
- Routed using logic inside the workflow

This project is built for **portfolio and demonstration purposes**.

---

## Use Case
Teams often receive requests via email, forms, or chat:
- Refund requests  
- Technical issues  
- Hiring updates  
- Reporting requests  

These are usually handled manually, which is slow and inconsistent.

This workflow shows how AI can assist by automatically classifying and prioritizing requests.

---

## Architecture
![Architecture Diagram](diagram.png)

Flow:
Webhook → AI Classification → JSON Parsing → Logic Routing → Action

---

## n8n Workflow
The workflow is located at:
