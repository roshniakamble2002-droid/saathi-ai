# 🧠 SaathiAI
### *Because every student deserves someone to talk to.*

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-actively--building-brightgreen)
![FOSS Hack](https://img.shields.io/badge/FOSS%20Hack-2026-orange)
![Made in India](https://img.shields.io/badge/Made%20with%20%F0%9F%92%99-India-blue)

---

## 💙 Why I built this

I'm a student. And like most students around me, I've seen what happens
when mental health is treated as a luxury — when asking for help feels
embarrassing, when therapy is too expensive, when there's simply
*no one to talk to at 2am before an exam.*

Mental health conversations in Indian colleges are either hushed or
completely absent. And the tools that exist? They're either paid,
English-only, or send your most private thoughts to some server
halfway across the world.

SaathiAI is my attempt to change that — even a little.

A free, offline, judgment-free space. Just for us. 🤝

---

## ✨ What SaathiAI does

- 💬 **Talks with you** — empathetic AI chat in English, Hindi & Hinglish
- 📊 **Tracks your mood** — log how you feel daily, see patterns over time
- 🚨 **Watches out for you** — detects crisis signals & shows Indian helplines
- 🔒 **Keeps your secrets** — runs 100% offline, zero data ever leaves your device
- 🆓 **Costs nothing** — no subscriptions, no hidden fees, no API bills

---

## 🛠️ How it's built

| Part | Tech |
|------|------|
| Frontend | React + Vite + Tailwind CSS |
| Backend | Python + FastAPI |
| AI Brain | Mistral (runs locally via Ollama) |
| Mood Charts | Chart.js |

The whole thing runs on your own machine.
No internet needed after setup. No cloud. No tracking. Just you and SaathiAI. 🌙

---

## 🚀 Run it yourself

### You'll need
- Node.js
- Python 3.11+
- [Ollama](https://ollama.com) installed

### Steps
```bash
# Clone the project
git clone https://github.com/roshniakamble2002-droid/saathi-ai.git
cd saathi-ai

# Download the AI model (one time, ~4GB)
ollama pull mistral

# Start the backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Start the frontend (open a new terminal)
cd frontend
npm install
npm run dev
```

Open `http://localhost:5173` and start talking 💙

---

## 🆘 If you or someone you know needs help right now

| Helpline | Number |
|----------|--------|
| iCall | 9152987821 |
| Vandrevala Foundation | 1860-2662-345 |
| AASRA | 9820466627 |

*You don't have to be in crisis to call. Sometimes you just need to talk.*

---

## 🗺️ What's coming

- [x] Project setup & architecture
- [ ] AI chat with Mistral
- [ ] Mood tracker + charts  
- [ ] Crisis keyword detection
- [ ] Hinglish language support
- [ ] Mobile responsive UI

---

## 🤝 Want to contribute?

This is a FOSS project — contributions are warmly welcome!
Found a bug? Have an idea? Open an issue or send a PR.
Even a kind star ⭐ means a lot when you're building solo at midnight.

---

## 📄 License

MIT — free forever. Because mental health tools shouldn't have paywalls.

---

*Built with a lot of chai, care, and sleepless nights by
[Roshni](https://github.com/roshniakamble2002-droid) 💙*

*FOSS Hack 2026*
