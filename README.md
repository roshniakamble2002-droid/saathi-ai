## 🚀 Demo

🎥 Demo Video: Coming soon
🧠 Live Preview: Coming soon

---

# 🧠 SaathiAI

### *Because every student deserves someone to talk to.*


\

---

## 💙 Why I built this

I’m a student, and like many others, I’ve seen how mental health is often overlooked in everyday student life.

During exams and high-pressure situations, many students struggle silently — not because they don’t want help, but because:

* Support can be expensive
* Talking about mental health still feels uncomfortable
* Most tools are not designed for students in our context

I wanted to change that — even in a small way.

So I built **SaathiAI** — a simple, private, and accessible AI companion designed especially for students.

💙 *A space where you can talk freely — anytime, without pressure or judgment.*

---

## ❗ Problem

Students today face increasing stress, anxiety, and pressure — especially during exams.

* Mental health support is not always accessible
* Students hesitate to open up due to social stigma
* Existing tools are often paid, English-only, or not privacy-focused
* Many solutions require constant internet access

---

## 💡 Solution

SaathiAI is an **offline AI mental health companion** built specifically for students.

* 🧠 Works anytime — no internet required
* 🔒 Fully private — runs locally on your device
* 💬 Supports conversations in English, Hindi & Hinglish
* ❤️ Provides supportive and empathetic interactions

---

## ✨ What SaathiAI does

* 💬 **Talks with you** — empathetic AI chat in English, Hindi & Hinglish
* 📊 **Tracks your mood** — log how you feel daily and see patterns over time
* 🚨 **Watches out for you** — detects crisis signals & shows Indian helplines
* 🔒 **Keeps your secrets** — runs 100% offline, zero data leaves your device
* 🆓 **Costs nothing** — no subscriptions, no hidden fees, no API bills

---

## 🛠️ How it's built

| Part        | Tech                              |
| ----------- | --------------------------------- |
| Frontend    | React + Vite + Tailwind CSS       |
| Backend     | Python + FastAPI                  |
| AI Brain    | Mistral (runs locally via Ollama) |
| Mood Charts | Chart.js                          |

The entire system runs on your own machine.
No internet needed after setup. No cloud. No tracking. Just you and SaathiAI. 🌙

---

## 🚀 Run it yourself

### You'll need

* Node.js
* Python 3.11+
* [Ollama](https://ollama.com) installed

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

| Helpline              | Number        |
| --------------------- | ------------- |
| iCall                 | 9152987821    |
| Vandrevala Foundation | 1860-2662-345 |
| AASRA                 | 9820466627    |

*You don’t have to be in crisis to call. Sometimes you just need someone to talk to.*

---

## 🗺️ What's coming

* [ ] Project setup & architecture
* [ ] AI chat with Mistral
* [ ] Mood tracker + charts
* [ ] Crisis keyword detection
* [ ] Hinglish language support
* [ ] Mobile responsive UI

---

## 📄 License

MIT — free forever. Because mental health tools shouldn’t have paywalls.

---

*Built with chai ☕, care 💙, and sleepless nights by*
[Roshani](https://github.com/roshniakamble2002-droid)
