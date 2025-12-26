🚀 **AI-Driven Marketing Automation with n8n**
**Project 3:**
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


**N8N Nodes -- Before Execution**
<img width="1769" height="522" alt="image" src="https://github.com/user-attachments/assets/b3f54175-d67f-410d-855c-b9c96438f8b6" />

**N8N Nodes -- After Execution**
<img width="1433" height="296" alt="image" src="https://github.com/user-attachments/assets/1aa95e97-635e-48e4-b4ec-ea1756684d39" />

**Slack Input & Post execution Acknowledgement:**
<img width="1417" height="875" alt="image" src="https://github.com/user-attachments/assets/7e20e49c-e0d8-443e-9592-0702007e6b5b" />

**Email Triggered to the customer's in Gsheet**
<img width="1628" height="1512" alt="image" src="https://github.com/user-attachments/assets/615ffe2b-91a1-47c9-b843-5c9e69859555" />

Output: 
Image: 
<img width="720" height="720" alt="image" src="https://github.com/user-attachments/assets/e97380b7-6608-4392-be79-7ed64bc49eb2" />

Video:
https://github.com/user-attachments/assets/fd7c5de5-2ffd-4ead-b446-9e8b733d73cb

**Project 2: N8N based customer email**
<img width="1801" height="1105" alt="image" src="https://github.com/user-attachments/assets/c638d8e9-2bce-4f9b-bebb-fe426dda8b95" />

**Project 1: N8N Welcome email to the customers in the Gsheet**
<img width="630" height="573" alt="image" src="https://github.com/user-attachments/assets/f78e8d72-7b54-4266-9bd6-8cb5ba4fc5ad" />




