# AI Workflow – Inbox Triage Automation (Python + n8n Demo)

## Overview
This is a demo project showing how **AI-powered workflows can automate internal task handling**, using both:
- Python for AI logic
- n8n-style workflow orchestration

It represents a realistic architecture used in business automation systems.

---

## What this demonstrates
- AI-based classification of incoming requests  
- Human-in-the-loop review point  
- Workflow-style orchestration (like n8n)  
- Practical application to operations workflows  

---

## Architecture
![Workflow Diagram](diagram.png)

Flow:
Webhook/Input → AI Classification → (Optional Human Review) → Routing/Action

---

## n8n Workflow
The file `n8n_workflow.json` contains a sample exported workflow showing how this logic would be implemented inside n8n.

Nodes included:
- Webhook trigger  
- AI classification step  
- Human approval logic  
- Routing logic  

This reflects how real automation systems are structured.

---

## Python AI Demo
The script in `src/ai_classifier.py` simulates the AI decision layer.

It:
- Uses OpenAI if API key is present  
- Falls back to simulated AI if not  
- Outputs structured JSON results  

Run it:
```bash
python src/ai_classifier.py
