🚀 **AI-Driven Marketing Automation with n8n**

**Overview**
This project demonstrates an end-to-end AI-powered marketing automation workflow built using n8n.
When a message is posted in a Slack channel (e.g., “Create 30% discount offer”), the workflow automatically generates marketing assets and distributes them across channels.

🔄 **Workflow Summary**

1.**Slack Trigger**
  Listens for new messages in a specific Slack channel.
  
2.**AI Content Generation**
   Poster Generation: Uses Nano Banana to create a sales promotion poster.
   Video Generation: Uses Veo 3.1 to generate an 8-second marketing video.
   
3. **Slack Acknowledgement**
   Posts the generated poster and video back to the Slack channel.
   
4. **Email Automation**
   Fetches recipient email IDs from Google Sheets.
   
   **Sends an email with:**

   Poster embedded inline in the email body

   Marketing video attached

**🛠️ Tech Stack**

Automation: n8n

Messaging: Slack

AI Models: Nano Banana (Image), Veo 3.1 (Video)

Data Source: Google Sheets

Email: SMTP / Gmail (configurable)

**📌 Use Case**

Marketing campaign automation

Instant promotional asset creation

AI-assisted content delivery

No-code / low-code workflow orchestration
