AI-Powered Customer Support Ticketing System

Project Overview

The AI-Powered Customer Support Ticketing System is a Salesforce-based project designed to assist customer support teams using Salesforce Agentforce and AI-powered suggested responses.

The system helps support agents generate suggested replies for customer cases, making customer communication more efficient.

Problem Statement

Customer support agents often spend significant time understanding customer issues and preparing responses. This project aims to simplify that process using AI-powered assistance within Salesforce.

Technologies Used

- Salesforce CRM
- Salesforce Agentforce
- Salesforce Prompt Builder
- Salesforce Flow / Salesforce Automation (where configured)
- Salesforce DX
- Git and GitHub

Key Features

- AI-powered customer support agent.
- Custom Agentforce subagent named CST Topic.
- AI Suggested Response prompt template.
- Case-based suggested response generation.
- Integration of a custom prompt template action with Agentforce.
- Salesforce metadata management using Salesforce DX.

How It Works

1. A user interacts with the AI Customer Support Agent.
2. The agent identifies a request related to a case suggested reply.
3. The agent asks for the Case ID.
4. The AI Suggested Response action is executed.
5. A suggested customer response is generated.

Project Structure

AI-Customer-Support-System/
│
├── force-app/
│   └── main/
│       └── default/
├── manifest/
│   └── package.xml
├── config/
├── scripts/
├── .gitignore
├── sfdx-project.json
└── README.md

Learning Outcomes

- Understanding Salesforce Agentforce.
- Creating custom Agentforce subagents.
- Working with Salesforce Prompt Builder.
- Configuring custom agent actions.
- Managing Salesforce metadata using Salesforce DX.
- Using Git and GitHub for version control.

Author

Anish-476

GitHub: https://github.com/Anish-476

---

This project was developed as a Salesforce learning and implementation project.
