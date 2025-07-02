Here’s your README with all emojis removed and a clean, modern tone:

---

# BlinkBrief - AI Article Summarizer Chrome Extension Powered by Gemini API

> Summarize articles instantly with one click using Generative AI.

---

### Built By: Nirali Bhargava

📧 [niralibhargava12@gmail.com](mailto:niralibhargava12@gmail.com)

---

## Overview

**AI Article Summarizer** is a lightweight **Chrome extension** that uses **Google’s Gemini API** to summarize any webpage you're currently viewing. With just one click, it extracts key insights and presents a clear, concise summary — directly in your browser.

No more skimming endless paragraphs — let AI do the reading for you.

---

## Tech Stack

| Category       | Tools & Libraries                           |
| -------------- | ------------------------------------------- |
| Extension Base | HTML, CSS, JavaScript                       |
| AI API         | Google Gemini Flash 1.5 (Generative AI)     |
| Scripts        | Manifest V3, Popup Scripts, Content Scripts |
| Deployment     | Chrome Extension Store / Manual Install     |

---

## Key Features

* Uses **Gemini Pro/Flash** for AI summarization
* One-click summarization of the active tab’s content
* Summary displayed in a clean popup window
* API key stored securely (locally)
* Lightweight, fast, and clutter-free interface

---

## Extension Structure

```
AI-Article-Summarizer/
├── manifest.json            → Chrome extension config (V3)
├── popup.html               → UI of the extension
├── popup.js                 → Handles API calls and rendering
├── content.js               → Pulls text from current page
├── style.css                → Extension styling
├── icons/                   → Browser action icons
└── config.js (local only)   → Gemini API key (DO NOT UPLOAD)
```

---

## How to Install Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/blinkbrief.git
```
2. Open Chrome and go to `chrome://extensions/`
3. Enable **Developer Mode** (top-right)
4. Click **Load unpacked** and select the project folder
5. Create  https://makersuite.google.com/app/apikey
6. Pin the extension and start summarizing

---

## Security Note

Your Gemini API key should **never be uploaded** or committed publicly. Use `.gitignore` to exclude `config.js` in version control.

---

## Future Features

* Support for summarizing PDFs or selected text
* Toggle for summary length (short/medium/detailed)
* Dark mode UI
* History of past summaries
* Multi-language support

---

## Why This Project?

* Demonstrates real-world **LLM integration** in browser tools
* Bridges frontend scripting with **modern AI** models
* Highlights **Chrome Extension** development skills
* Transforms generative AI into a **practical daily tool**

---
