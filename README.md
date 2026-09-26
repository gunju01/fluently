# Fluently — Voice-First English Learning Chatbot

Fluently is a free, AI-powered English learning app that runs entirely in your browser. No installation, no accounts, no servers — just one HTML file and an API key.

Practice speaking, reading, writing, and pronunciation with real-time AI feedback. Fluently uses speech recognition and text-to-speech built into your browser, so your conversations feel natural and interactive.

**[Try it live →](https://your-username.github.io/fluently/)**

---

## Features

### Conversation Practice
Chat with an AI tutor that adapts to your English level. Speak or type your messages, and get real-time corrections on grammar, vocabulary, and pronunciation. The AI responds with voice so you can practice listening too.

### Reading Practice
Read AI-generated articles aloud and get scored on your pronunciation accuracy. Words you mispronounce are highlighted so you know exactly what to work on. Difficulty adjusts to your level (A1–C2).

### Speaking Practice
Have free-form speaking sessions on any topic. The AI listens to you speak, transcribes what you said, and gives detailed feedback on fluency, grammar, vocabulary, and pronunciation.

### Writing Practice
Write paragraphs on prompted topics and receive scored feedback (out of 10) on grammar, vocabulary, and structure. Corrections are shown inline so you can learn from each mistake.

### Pronunciation Lab (Sounds)
Practice specific English sounds (TH, R, L, S vs SH, and more) with targeted word drills. Listen to the correct pronunciation, then try saying the word in a sentence. The app checks if you pronounced the target sound correctly.

### Vocabulary & Learning
Build your vocabulary through conversations. New words are collected and tracked, with definitions and example sentences you can review anytime.

### Progress Dashboard
Track your growth with detailed stats: daily activity, XP and leveling system, streak tracking, score trends for reading and writing, skill breakdowns, and focus area recommendations.

### Gamification
Earn XP for every activity, level up through 12 ranks (Beginner → Legend), and maintain daily streaks to stay motivated.

### Export & Import Progress
Back up all your progress to a JSON file and restore it on any device or browser. Never lose your learning data.

---

## Getting Started

### 1. Get a Free API Key

Fluently needs an AI API key to power the conversations. You have three options:

| Provider | Free Tier | How to Get Key |
|----------|-----------|----------------|
| **Google Gemini** (Recommended) | Generous free usage | [aistudio.google.com/apikey](https://aistudio.google.com/apikey) |
| **OpenAI** | Paid (pay-per-use) | [platform.openai.com/api-keys](https://platform.openai.com/api-keys) |
| **OpenRouter** | Some free models | [openrouter.ai/keys](https://openrouter.ai/keys) |

**Google Gemini is recommended** — it has a generous free tier that's more than enough for daily practice.

### 2. Open the App

**Option A: Use the hosted version**
Visit the live link: **[https://your-username.github.io/fluently/](https://your-username.github.io/fluently/)**

**Option B: Run locally**
1. Download `index.html` from this repository
2. Double-click to open it in your browser
3. That's it — no server needed

### 3. Connect Your API Key

1. When the app opens, select your AI provider (Gemini, OpenAI, or OpenRouter)
2. Paste your API key
3. Click **"Connect & Start"**
4. Start learning!

---

## API Providers Comparison

### Google Gemini (Recommended)
- **Cost:** Free tier with generous limits
- **Models used:** gemini-2.5-flash, gemini-3.5-flash-lite
- **Pros:** Free, fast, good quality responses
- **Best for:** Most users, daily practice
- **Get key:** [aistudio.google.com/apikey](https://aistudio.google.com/apikey)

### OpenAI
- **Cost:** Pay-per-use (~$0.01–0.03 per conversation)
- **Models used:** gpt-4o-mini
- **Pros:** High quality corrections, natural conversations
- **Best for:** Users who want premium quality and don't mind paying
- **Get key:** [platform.openai.com/api-keys](https://platform.openai.com/api-keys)

### OpenRouter
- **Cost:** Varies (some free models available)
- **Models used:** Various (auto-selects best available)
- **Pros:** Access to many models, some free options
- **Best for:** Users who want to experiment with different AI models
- **Get key:** [openrouter.ai/keys](https://openrouter.ai/keys)

---

## How to Use Each Feature

### Chat
1. Click the **Chat** tab
2. Type a message or click the **microphone** button to speak
3. The AI will respond and correct any mistakes
4. Click on corrections to learn and practice them

### Reading Practice
1. Click the **Practice** tab
2. Choose a difficulty level and topic
3. Read the article aloud — click the microphone to start
4. Get your accuracy score and see which words to improve

### Speaking Practice
1. Click the **Speak** tab
2. Choose a topic or speak freely
3. Record yourself speaking for as long as you want
4. Get detailed feedback on fluency, grammar, and pronunciation

### Writing Practice
1. Click the **Writing** tab
2. Get a writing prompt or choose your own topic
3. Write your response
4. Receive a scored evaluation with specific corrections

### Pronunciation Lab
1. Click the **Sounds** tab
2. Pick a sound pair to practice (e.g., TH vs T)
3. Listen to each word, then click **Try** to practice
4. Say the example sentence — the app checks your pronunciation

### Progress Tracking
1. Click the **Progress** tab to see your growth dashboard
2. View daily stats, weekly charts, and score trends
3. Use **Export** to back up your data
4. Use **Import** to restore data on another device

---

## Tech Stack

- **Frontend:** Vanilla HTML, CSS, and JavaScript — single file, no build tools, no framework
- **AI:** Google Gemini / OpenAI / OpenRouter APIs (user provides their own key)
- **Speech Recognition:** Web Speech API (built into Chrome, Edge, Safari)
- **Text-to-Speech:** Web Speech Synthesis API (built into browsers)
- **Storage:** Browser localStorage (all data stays on your device)
- **Hosting:** GitHub Pages (free, static hosting)

---

## Privacy & Security

- **Your API key stays in your browser** — it's stored in localStorage and never sent to any server except the AI provider you chose
- **No tracking, no analytics, no cookies** — the app collects zero data about you
- **No backend server** — everything runs client-side in your browser
- **Your progress data is yours** — export it anytime as a JSON file

---

## Browser Support

| Browser | Support |
|---------|---------|
| Google Chrome | Full support (recommended) |
| Microsoft Edge | Full support |
| Safari | Partial (speech recognition may be limited) |
| Firefox | Limited (no speech recognition) |

**Chrome or Edge on desktop is recommended** for the best experience with voice features.

---

## Self-Hosting

Since Fluently is a single HTML file, you can host it anywhere:

- **GitHub Pages** (this repo) — free, easy
- **Netlify / Vercel** — drag and drop the file
- **Any web server** — just serve `index.html`
- **Local** — double-click the file to open in your browser

---

## Contributing

Contributions are welcome! Since this is a single-file app:

1. Fork this repository
2. Edit `index.html`
3. Test by opening it in your browser
4. Submit a pull request

---

## License

MIT License — free to use, modify, and distribute.

---

Built with AI, for learning with AI.
