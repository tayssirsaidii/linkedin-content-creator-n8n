AI-powered LinkedIn content generation workflow built using n8n.

This automation system streamlines the process of creating professional LinkedIn posts by combining web research, AI-generated writing, and automated content management. The workflow retrieves trending or relevant information, processes it through AI models, and generates engaging LinkedIn-ready content automatically.

Features
Automated LinkedIn content generation
AI-powered post writing
Web research integration with Tavily API
Google Sheets integration for topic management
OpenRouter AI model integration
Automated workflow orchestration
Content storage and management
Professional post formatting
Workflow Architecture

(Add workflow screenshots here)

Example:

![Workflow Overview](screenshots/workflow-overview.png)
Tech Stack
n8n
OpenRouter
Tavily API
Google Sheets API
REST APIs
JSON
AI/LLM Integration
Workflow Process
Topics are retrieved from Google Sheets
Tavily API gathers relevant web information and articles
AI agent processes the research data
OpenRouter models generate professional LinkedIn posts
Generated content is automatically stored in Google Sheets
Posts are ready for publishing or scheduling
Use Cases
Personal branding automation
LinkedIn content marketing
Social media management
AI-powered content creation
Professional networking growth
Automated post drafting
Import Workflow
Download the workflow JSON file
Import the workflow into n8n
Configure API credentials:
OpenRouter API
Tavily API
Google Sheets API
Update spreadsheet references if needed
Run the workflow
