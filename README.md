# OpenTTS-Festival
OpenTTS-Festival is an Open Source TTS that can be Deployed on Render and use it for Make.com and n8n Workflows

📝 Deployment steps

1. Create a new GitHub repo (e.g. my-opentts-festival) and push these files.


2. In Render Dashboard:

Click New → Web Service

Connect to your GitHub repo

Confirm name, environment (Docker), Dockerfile path

Set port to 5500, choose Free plan, enable Auto‑deploy



3. Render will build and deploy — you'll get a live URL.




---

⏩ Next Steps: Integrate with n8n / Make.com

Once your Render service is live:

1. Webhook Trigger: send POST { "text": "your message" }


2. HTTP Request to your TTS endpoint (like above)


3. Store the MP3 — send it to Google Drive or Airtable
