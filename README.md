# 🧠 AlignAI

**Own your time.**  
AlignAI is a natural-language, AI-powered calendar assistant that helps you manage meetings, resolve conflicts, and stay organized — effortlessly.

---

## 🏆 Highlights

- Built with **Next.js**, **ShadCN/UI**, **OpenAI GPT-4**, and **Firestore**
- Integrated **GPT-4 Function Calling** for intelligent scheduling decisions
- Supports **Google login** and upcoming **Google Calendar sync**
- Features built-in **text-to-speech** for a human-like assistant experience

---

## ✨ Features

- 📅 Natural language scheduling: “Find 30 free minutes next week for a meeting”
- 🤝 AI conflict resolution: Detects overlaps and suggests alternative times
- 🧠 GPT-4 powered assistant: Ask “When are Alex and I both free next week?”
- 🔊 Text-to-speech: Your assistant talks back for a more intuitive feel
- ⏳ Real-time countdowns to events and meetings
- 🔐 Google authentication with seamless onboarding

---

## 🛠️ Tech Stack

| Layer       | Tools                                      |
|------------|---------------------------------------------|
| Frontend   | Next.js, ShadCN/UI                          |
| Backend    | OpenAI GPT-4 (Function Calling), Firestore  |
| Auth       | Google OAuth (NextAuth)                     |
| AI Core    | GPT-4-powered logic for conflict detection and slot selection |
| Hosting    | Vercel (recommended)                        |

---

## 🧩 How It Works

1. **Sign in** with your Google account  
2. **Talk to AlignAI** using natural language (e.g., "Book a call with Aisha next Wednesday")  
3. **AlignAI processes your request**, checks for conflicts, and suggests the best times  
4. **Text-to-speech** responds back to you like a real assistant  
5. **(Coming soon)**: Full Google Calendar sync and event auto-scheduling

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alignai.git
   cd alignai
2. Install dependencies:
   ```bash
   npm install
3. Set up env variables in .env.local:
   NEXT_PUBLIC_OPENAI_API_KEY=your-openai-key
   GOOGLE_CLIENT_ID=your-google-client-id
   GOOGLE_CLIENT_SECRET=your-google-client-secret
   FIREBASE_PROJECT_ID=your-firebase-project-id
   FIREBASE_CLIENT_EMAIL=your-firebase-client-email
   FIREBASE_PRIVATE_KEY=your-firebase-private-key
4. Run the development server:
   ```bash
   npm run dev
5. Visit http://localhost:3000 in your browser.
