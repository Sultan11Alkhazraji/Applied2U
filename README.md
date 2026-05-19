# Applied2u — Insight Curator & Growth Partner

<div align="center">

![Gemma 4 Good Hackathon](https://img.shields.io/badge/Gemma-4-Good-Hackathon-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Live Demo](https://img.shields.io/badge/Live-Demo-Online-brightgreen?style=flat-square)

**Turn any content into your personalized 30-day growth plan, powered by Google Gemma 4 AI**

[🚀 Live Demo](https://sultan11alkhazraji.github.io/applied2u/) · [📂 Code](https://github.com/Sultan11Alkhazraji/Applied2U) · [🎥 Demo Video](https://www.youtube.com/watch?v=your-video-id)

</div>

---

## 📋 Description

Applied2u is a web application that extracts key insights from any content (articles, PDFs, URLs) and transforms them into actionable growth plans. Using Google's **Gemma 4 AI model**, it delivers:

- ⭐ **The One Thing** — The single most important takeaway
- 💡 **Key Insights** — 5-7 actionable bullet points
- ✅ **Action Steps** — Specific tasks to do this week
- 🗓️ **30-Day Growth Plan** — Detailed weekly tasks with interactive checkboxes

### Key Features

| Feature | Description |
|---------|-------------|
| ☁️ **Cloud Mode** | Use Google AI Studio API |
| 🖥️ **Local Mode** | Run Gemma 4 offline via LM Studio, Ollama, Jan |
| 📄 **PDF Support** | Upload and analyze PDF documents |
| 🔗 **URL Support** | Enter any article URL |
| ✏️ **Text Input** | Paste content directly |
| ✅ **Checklists** | Track progress with interactive checkboxes |
| 📥 **Export** | Download as Markdown |
| 📧 **Email** | Send plan via email |
| 📅 **Calendar** | Add tasks to Google Calendar |

---

## 🚀 Quick Start

### Cloud Mode (Online)

1. Open [Applied2u Live Demo](https://sultan11alkhazraji.github.io/applied2u/)
2. Select **Cloud API** mode
3. Get a free API key from [Google AI Studio](https://aistudio.google.com/apikey)
4. Enter your API key
5. Paste content, upload PDF, or enter URL
6. Click **Extract Insights & Build My Action Plan**

### Local Mode (Offline/Privacy-First)

1. Download [LM Studio](https://lmstudio.ai/)
2. Download a Gemma 4 model (e.g., `google/gemma-4-27b-a4b`)
3. Start the local server
4. Open the app in your browser
5. Select **Local** mode
6. Click "Check connection" to verify
7. Enter content and analyze

---

## 🛠️ How It Works

### Architecture

```
┌─────────────────────────────────────────────────────────┐
│                     Applied2u                           │
├─────────────────────────────────────────────────────────┤
│  Input Methods:                                        │
│  ├── Text (paste)                                      │
│  ├── PDF (upload)                                      │
│  └── URL (fetch)                                       │
├─────────────────────────────────────────────────────────┤
│  AI Processing:                                        │
│  ├── Google AI Studio (Cloud)                          │
│  └── OpenAI-Compatible API (Local)                     │
├─────────────────────────────────────────────────────────┤
│  Output:                                               │
│  ├── The One Thing                                     │
│  ├── Key Insights                                      │
│  ├── Action Steps                                      │
│  └── 30-Day Growth Plan                                │
├─────────────────────────────────────────────────────────┤
│  Exports: Markdown | Email | Google Calendar           │
└─────────────────────────────────────────────────────────┘
```

### Prompt Engineering

Applied2u uses carefully crafted prompts to get structured output from Gemma 4:

- Custom output format for each section
- Context-aware content truncation based on detected model context length
- Retry logic for multiple Gemma model variants

---

## 📸 Examples

### Input: Spanish Learning Article
- **The One Thing**: "Consistency and immersion are more critical than raw intelligence when mastering a new language"
- **30-Day Plan**: Specific daily tasks like "Download Anki deck and memorize 10 nouns each morning"

### Input: First Aid Manual
- **The One Thing**: "Rapid mastery of systematic protocols transforms paralyzing panic into controlled, life-saving response"
- **30-Day Plan**: Week-by-week tasks for CPR, AED usage, emergency response

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgments

- [Google DeepMind](https://deepmind.google/) — Gemma 4 model
- [Gemma 4 Good Hackathon](https://www.kaggle.com/competitions/gemma-4-good-hackathon) — Competition
- [LM Studio](https://lmstudio.ai/) — Local inference
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF parsing
