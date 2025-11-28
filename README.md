# Interview Prep Flashcards – MVP

This repository contains the MVP (Minimum Viable Product) for my **Interview Prep Flashcard Web App**, built for my Rize / COMPS course.  
The purpose of the MVP is to demonstrate professional development workflows including AI-assisted development, Docker containerization, Git branching, and cloud deployment — not to build the full final app yet.

---

# 🎯 MVP Scope (Unit 12)

The MVP includes:

- A simple flashcard review interface (flip card, Got it/Missed it)
- Static frontend served by Node.js + Express
- Containerized application using Docker
- Deployment attempt on Google Cloud Run
- Documentation using README + Jira + Confluence
- AI-assisted development using GitHub Copilot and ChatGPT

This fulfills all required MVP grading criteria.

---

# 🧱 Architecture (MVP Version)

### **Frontend**
- HTML, CSS, JavaScript  
- Located in `/public` folder  
- Flashcards stored temporarily in local session data (not persistent)

### **Backend**
- Node/Express (`server.js`) serving static assets  
- Listens to `PORT` (Cloud Run requirement)

### **Deployment**
- Docker container (Node 18 Alpine)  
- Deployed using Google Cloud Run  
- Cloud Run URL included in submission (even if broken)

---

# 🤖 AI Tools Used During Development

### **GitHub Copilot**
- Suggested Express boilerplate for `server.js`
- Helped generate event-handling logic for flashcard flipping
- Improved JavaScript loops and UI update logic

### **ChatGPT**
- Assisted debugging port issues for Cloud Run
- Helped structure Jira user stories & Confluence documentation

_All AI-generated content was reviewed and edited before being committed._

---

# 🧪 Running the MVP Locally

```bash
npm install
npm start
# or
node server.js
