# AI-Podcast-Generator
An AI Powered Podcast generator that takes text prompt from the user and converts into podcast audio format.

🚀 How It Works
  -Webhook Trigger Receives a topic via HTTP POST request.
  -Podcast Script Generation (Google Gemini)=> Uses Google Gemini to generate a 2-minute engaging podcast script based on the given topic.
  -Voice Generation (Murf AI)=> Converts the generated script into natural-sounding speech using Murf AI’s voice model.
  -Audio Download=> Automatically downloads the generated podcast audio file.
  -Webhook Response Returns the final result back to the user.

🛠 Tech Stack
  n8n – Workflow Automation
  Google Gemini API – AI Script Generation
  Murf AI API – Text-to-Speech Voice Generation
  HTTP Webhooks – API Trigger & Response Handling

📌 Features
  ✔ Fully automated AI podcast generation
  ✔ 2-minute structured podcast scripts
  ✔ Natural human-like voice output
  ✔ Webhook-based API integration
  ✔ Scalable & customizable workflow

📂 Use Case
  AI Content Automation
  Podcast Production Automation
  Content Creator Tools
  No-Code / Low-Code AI Projects
  AI SaaS Prototype Development
