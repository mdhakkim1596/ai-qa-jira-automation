# AI QA Bug-to-Jira Automation
  - AI-powered n8n workflow that converts natural-language QA bug reports into structured Jira issues using Google Gemini.

# Workflow
User → n8n Chat Trigger → AI Agent → Google Gemini
                              ↓
                         Jira Tool
                              ↓
                        Jira Issue

# Features
  - AI-powered bug analysis
  - Automatic Jira Summary generation
  - Structured bug description
  - Steps to Reproduce
  - Actual & Expected Results
  - Automatic Jira issue creation
  - File upload support

# Technologies
  - n8n
  - Google Gemini
  - Jira Software
  - AI Agent
  - Workflow Automation
  - Prompt Engineering

# Project Structure
ai-qa-jira-automation/
├── README.md
├── .gitignore
├── workflows/
│   └── qa-jira-automation-demo.json
├── prompts/
│   └── jira-agent-system-prompt.txt
└── screenshots/
    ├── n8n-workflow.png
    └── jira-ticket.png

# Jira Summary Format
[Feature or Module] - [Concise Description of the Defect]

# Purpose
  - Demonstrates how AI and workflow automation can reduce repetitive QA activities by converting bug reports into structured Jira issues.
