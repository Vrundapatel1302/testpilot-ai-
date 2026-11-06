# TestPilot AI 🚀

**TestPilot AI** is a lightweight Chrome extension that eliminates the friction of writing UI automation scripts. It allows QA and Automation Engineers to inspect web elements directly on any live webpage, extract stable DOM attributes, and instantly generate production-ready test code using AI.

---

## ✨ Features

- **🎯 Smart Locator Selection:** Prioritizes resilient selectors (`data-testid`, `aria-label`, semantic attributes) over brittle, dynamic CSS or deep XPaths.
- **🎨 Codebase Style Matching:** Accepts custom code reference examples from your existing repo to output matching Page Object Model (POM) methods or inline test scripts.
- **⚡ One-Click DOM Inspection:** Injects an interactive hover inspector directly into any active webpage to isolate elements safely.
- **🛠 Multi-Framework Support:** Ready for Playwright (TypeScript/JavaScript), Cypress, and Selenium.
- **🔒 Secure & Local:** Uses your own API keys stored safely inside Chrome local storage.

---

## 🛠 Tech Stack

- **Frontend/UI:** HTML5, CSS3, JavaScript (Chrome Extension V3)
- **Core Scripts:** Chrome Content Scripts & Event Background Service Workers
- **AI Integration:** OpenAI / Gemini API (LLM Gateway)

---

## 🚀 Installation & Setup

### Prerequisites
- Google Chrome Browser
- An API Key from your preferred LLM provider (e.g., OpenAI or Google Gemini)

### Steps

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/testpilot-ai.git](https://github.com/your-username/testpilot-ai.git)
   cd testpilot-ai
