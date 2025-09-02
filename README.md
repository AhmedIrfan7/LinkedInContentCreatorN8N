# LinkedIn Content Creator Workflow

This n8n workflow automates the creation of LinkedIn-ready posts.  
It pulls topics from a Google Sheet, fetches recent web content via Tavily, summarizes insights with AI, and saves the final post back to the sheet.

## Features
- ✅ Fetches "To Do" topics from Google Sheets  
- 🌍 Uses Tavily API to gather recent web insights  
- 🤖 AI-powered summarization into professional LinkedIn content  
- ✍️ Updates the sheet with generated post and status  

## Workflow Steps
1. **Manual Trigger** – Start workflow on demand.  
2. **Google Sheets** – Get topic rows marked as "To Do".  
3. **HTTP Request** – Query Tavily API with the topic.  
4. **AI Agent** – Generate concise, engaging LinkedIn post (under 200 words).  
5. **Google Sheets** – Update row with content and mark as "Created".  

## Requirements
- n8n instance  
- Google Sheets API credentials  
- Tavily API key  
- OpenRouter account (for AI generation)  

## Usage
1. Import the workflow JSON into your n8n instance.  
2. Configure credentials for Google Sheets, Tavily, and OpenRouter.  
3. Add topics to your sheet with status "To Do".  
4. Execute the workflow – your LinkedIn post will be generated automatically.  

---
🚀 Save time and create high-quality LinkedIn content effortlessly.
