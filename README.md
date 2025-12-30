AI Agent Chat Automation Workflow using n8n

This repository contains an AI Agent based automation workflow built using n8n. The workflow listens to chat messages, generates creative and human-like responses using an OpenAI Chat Model, stores conversation context using memory, and automates actions such as email drafting and Google Sheets updates.

Workflow Overview

Flow sequence:
1. When Chat Message Received
2. AI Agent
3. OpenAI Chat Model
4. Simple Memory
5. Create Email Draft in Gmail
6. Get or Store Rows in Google Sheets

This workflow enables intelligent, creative, and context-aware automation.

Key Features

- Creative and natural language responses
- AI Agent powered by OpenAI Chat Model
- Memory-enabled conversations
- Automated Gmail draft creation
- Google Sheets integration
- Fully automated chat-based workflow

AI Agent Configuration

The AI Agent is configured to generate creative, friendly, and human-like responses, avoid repetitive or robotic outputs, and use memory to maintain conversation context.

Example prompt logic:
Generate a creative, friendly, and personalized response based on the incoming chat message.

Nodes Used

- Chat Trigger
- AI Agent
- OpenAI Chat Model
- Simple Memory
- Gmail
- Google Sheets

How to Use This Workflow

1. Download the workflow JSON file from this repository
2. Open your n8n dashboard
3. Click Import Workflow
4. Upload the JSON file
5. Configure OpenAI, Gmail, and Google Sheets credentials
6. Activate the workflow
7. Start sending chat messages

Use Cases

- Chat-based AI assistants
- Automated email drafting
- Creative message generation
- Customer communication automation
- AI-powered workflow orchestration

Customization

- Adjust model temperature for creativity
- Modify system prompts to change tone
- Extend the workflow with additional integrations
- Add logging or analytics nodes if required

Author

Shanmuga Priya  
1st Year CSE AI and ML Student  
Aspiring AI Engineer

License

This project is open-source and intended for educational and personal use.
