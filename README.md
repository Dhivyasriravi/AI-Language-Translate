# 🗣️ AI Language Translator

> Type or speak in any language — AI translates to 15+ languages in real time using Groq AI. Includes voice input, text-to-speech, translation history, and quick phrases.

**Built by:** Dhivyasri Ravi | CSE Graduate 2026

---

---

##  About the Project
A real-time AI-powered language translator that supports 15+ languages including Indian regional languages (Tamil, Hindi, Telugu, Kannada, Malayalam). Users can type or speak their input, hear the translation spoken aloud, and view their full translation history — all in a single HTML file with no installation required.

---

##  Features
-  Translates between 15+ languages including Tamil, Hindi, Telugu, Kannada, Malayalam, French, Spanish, German, Japanese, Chinese, Arabic, Korean, Portuguese, Russian, Italian
-  Auto language detection
-  Voice input — speak and it auto-translates (Chrome)
-  Text-to-speech — hear the translation read aloud
-  Swap languages with one click
   Quick phrase chips for common sentences
-  Copy translation to clipboard
-  Translation history log (last 15 translations)
-  Ctrl+Enter keyboard shortcut for fast translation
-  Galaxy particle animation background
-  Responsive design — works on mobile & desktop

---

##  Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / JavaScript | Frontend |
| Groq API (LLaMA 3.3 70B) | AI translation (free) |
| Web Speech API | Voice input (mic) & text-to-speech |
| Canvas API | Galaxy particle background animation |

---

##  Supported Languages

| Language | Flag | Language | Flag |
|---|---|---|---|
| English | 🇬🇧 | Tamil | 🇮🇳 |
| Hindi | 🇮🇳 | Telugu | 🇮🇳 |
| Kannada | 🇮🇳 | Malayalam | 🇮🇳 |
| French | 🇫🇷 | Spanish | 🇪🇸 |
| German | 🇩🇪 | Japanese | 🇯🇵 |
| Chinese | 🇨🇳 | Arabic | 🇸🇦 |
| Korean | 🇰🇷 | Portuguese | 🇵🇹 |
| Russian | 🇷🇺 | Italian | 🇮🇹 |

---

##  How to Run

### Step 1 — Get Free Groq API Key
```
1. Go to https://console.groq.com
2. Sign up with Gmail (free, no credit card needed)
3. Click "API Keys" → "Create API Key"
4. Copy the key (starts with gsk_...)
```

### Step 2 — Add API Key to Code
```javascript
// Open ai_language_translator.html in VS Code
// Find this line and replace:
const GROQ_KEY = 'YOUR_GROQ_API_KEY_HERE';
// With your real key:
const GROQ_KEY = 'gsk_yourrealkeyhere';
```

### Step 3 — Run
```
Option A: Open directly in Google Chrome (double-click)
Option B: VS Code → Right-click → Open with Live Server
Option C: Deploy on GitHub Pages (see below)
```

>  Voice input (🎤 Speak) works only in Google Chrome

---

##  Deploy on GitHub Pages (Free Hosting)
```
1. Create GitHub repo: ai-language-translator
2. Upload the HTML file → rename to index.html
3. Go to Settings → Pages → select main branch → Save
4. Live at: https://yourusername.github.io/ai-language-translator
```

---

##  Project Structure
```
ai-language-translator/
│
├── index.html        ← Complete project (single file)
└── README.md         ← Documentation
```

---

##  How It Works
1. User types text or speaks via microphone (Web Speech API)
2. Text is sent to Groq API with a translation prompt
3. LLaMA 3.3 70B model returns the translated text
4. Output is displayed and can be spoken aloud via SpeechSynthesis API
5. Each translation is saved to the history log

---

##  Future Improvements
- [ ] Support PDF/document translation
- [ ] Add romanization (transliteration) for non-Latin scripts
- [ ] Offline translation using smaller local models
- [ ] Browser extension version

---

##  Author
**Dhivyasri Ravi**
-  dhivyasriravi5@gmail.com
-  [LinkedIn](https://www.linkedin.com/in/dhivyasri1603/)
-  [GitHub](https://github.com/Dhivyasriravi)

---

##  License
MIT License — free to use and modify.

