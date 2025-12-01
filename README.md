# Sentinel – AI-Assisted Post-Implementation Support Platform

Sentinel is a functional demo that shows how ticketing, documentation and 
an AI assistant can work together to support clients and technical teams 
after a project goes live.

---

## 🚨 Problem

After implementations (infra, cameras, software, security changes), 
clients usually struggle with:

- Multiple channels for support (email, WhatsApp, calls)
- Scattered documentation
- No clear ownership of incidents
- Slow and manual triage

---

## ✅ Sentinel – Demo Solution

This demo centralizes post-implementation support in one place:

### For Clients
- Create tickets with title, description and priority
- Track ticket status (`New`, `In Progress`, `Resolved`)

### For Internal Teams
- See all tickets in a simple dashboard
- Update status and manage the queue

### For Everyone
- Search a **Knowledge Base** of articles
- Ask an **AI Assistant** (simulated) that suggests solutions based on keywords

> In a real implementation, the AI could be backed by OpenAI, a vector DB, 
> or an internal knowledge index. In this demo we simulate that behaviour.

---

## 🧩 Tech Stack

- **Frontend:** React + Vite
- **State:** React hooks + `localStorage`
- **Styling:** Simple CSS (no framework, easy to extend)
- **Demo only:** No real backend. Data is stored in the browser.

---

## 🏁 How to Run Locally

```bash
git clone https://github.com/luke7606/Sentinel.git
cd Sentinel

cd frontend
npm install
npm run dev
