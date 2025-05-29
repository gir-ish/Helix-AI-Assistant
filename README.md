# Helix: An AI Assistant 🤖

Helix is a next-generation virtual call-center solution, harnessing agentic AI and advanced NLP to deliver 24/7 personalized support across voice, WhatsApp, and web chat. By integrating your business knowledge via Retrieval-Augmented Generation (RAG) and open-source LLMs, Helix adapts seamlessly to your brand’s tone, handles appointments and orders, and provides real-time analytics—all within a secure, scalable architecture.

---

## ✨ Core Highlights

- **Omni-Channel Engagement**  
  Integrates Twilio voice calls, WhatsApp Business API, and web chat for a unified customer journey.  
- **Knowledge-Grounded AI (RAG)**  
  Pulls from your FAQ/KB documents in Pinecone to produce accurate, context-aware responses.  
- **Custom AI Personas**  
  Define greetings, tone, and signature messages that reflect your brand identity.  
- **Automated Scheduling & Orders**  
  Link directly to your REST API for real-time booking, cancellations, and order tracking.  
- **Interactive Dashboards**  
  Monitor usage, success metrics, and conversation logs through a sleek React admin portal.  
- **Robust & Secure**  
  FastAPI backend, MongoDB Atlas, Pinecone vector search, RBAC auth, and end-to-end TLS encryption.

---

## 🎥 Live Demo

> Click the thumbnail below to watch a brief walkthrough of Helix in action.

[![Helix Demo](docs/video/demo_thumbnail.png)](v1.mp4)

> Alternatively, you can **[play the demo video directly](v1.mp4)**.

**Instructions:**  
1. Place your thumbnail image at `docs/video/demo_thumbnail.png` (a frame-grab from the video).  
2. Place your video file at the repo root as `v1.mp4`.  
3. Clicking the thumbnail or link will launch GitHub’s native player for `v1.mp4`.

---

## 🚀 Quick Links

- **Doctor Login Portal**  
  https://aimshelix.ownbizaccount.com/doctor_login.html  
- **Client Dashboard**  
  https://helixclient.ownbizaccount.com/  
- **Admin Portal**  
  https://helix.ownbizaccount.com/  

---

## 🛠️ Tech Stack & Architecture

| Layer            | Technology                                    |
| ---------------- | --------------------------------------------- |
| **Frontend**     | React.js • Tailwind CSS • Material UI         |
| **Backend**      | FastAPI • Uvicorn (Python)                    |
| **Databases**    | MongoDB Atlas • Pinecone Vector Store         |
| **AI / ML**      | LangChain • Open-Source LLMs • RAG Pipelines   |
| **Comm. APIs**   | Twilio Voice • WhatsApp Business API          |
| **Security**     | RBAC • TLS Encryption                         |

---

## ⚙️ Getting Started

1. **Clone**  
   ```bash
   git clone https://github.com/your-org/helix-ai-assistant.git
   cd helix-ai-assistant
