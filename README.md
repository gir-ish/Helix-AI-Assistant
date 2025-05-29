# Helix: An AI Assistant

**Helix** is a smart, scalable virtual call-center solution powered by agentic AI and advanced Natural Language Processing. It delivers 24/7, personalized customer engagement across multiple channels—voice, WhatsApp, and web chat—while seamlessly integrating business-specific data via Retrieval-Augmented Generation (RAG) and open-source LLMs.

---

## Key Features

- **Multi-Channel Communication**  
  Voice calls (via Twilio), WhatsApp Business API, and web chat for a consistent user experience.
- **Retrieval-Augmented Generation (RAG)**  
  Dynamic retrieval of business knowledge (FAQs, documents) from Pinecone vector store to ground responses.
- **Custom AI Personas**  
  Business-specific persona configuration (tone, greeting, closing templates).
- **Appointment & Order Processing**  
  Real-time scheduling and order management through REST API integration.
- **Admin Dashboard**  
  React-based UI for business setup, analytics (interaction logs, conversion metrics), and monitoring.
- **Scalable & Secure Architecture**  
  FastAPI backend, MongoDB Atlas for structured data, Pinecone for vector searches, RBAC authentication, and TLS encryption.

---

## Media

### Screenshots

<p align="center">
  <img src="docs/images/doctor_login.png" alt="Doctor Login Portal" width="400" />
  <img src="docs/images/client_dashboard.png" alt="Client Dashboard" width="400" />
</p>

### Demo Video

<video width="800" controls>
  <source src="docs/videos/helix_demo.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>

*Alternatively, link to a hosted video (YouTube, Vimeo):*

[![Watch the Helix Demo](docs/images/demo_thumbnail.png)](https://youtu.be/your-demo-video)

---

## Architecture & Tech Stack

- **Frontend:** React.js, Material UI, Tailwind CSS  
- **Backend:** FastAPI (Python), Uvicorn  
- **Databases:**  
  - MongoDB Atlas for user/session/appointment data  
  - Pinecone for vector embeddings supporting RAG  
- **AI/ML Layer:** Open-source LLMs, LangChain, Retrieval-Augmented Generation  
- **Communication APIs:** Twilio (voice), WhatsApp Business API  

---

## Quick Links

- **Doctor Login Portal:**  
  https://aimshelix.ownbizaccount.com/doctor_login.html  
- **Client Dashboard:**  
  https://helixclient.ownbizaccount.com/  
- **Admin Portal:**  
  https://helix.ownbizaccount.com/  

---

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-org/helix-ai-assistant.git
   cd helix-ai-assistant
