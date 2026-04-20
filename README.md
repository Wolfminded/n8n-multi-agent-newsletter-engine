# Multi-Agent SEO Content Engine

**I built a fully autonomous AI-powered newsletter factory in n8n.**

This multi-agent system takes a simple form submission (topic + audience + tone) and automatically:
- Researches trending insights
- Creates an engaging table of contents
- Generates 4 fully researched sections with inline citations
- Edits and formats everything into beautiful HTML
- Adds a compelling subject line
- Delivers the finished newsletter straight to your inbox

Zero manual writing. Professional quality. Scales effortlessly.

![Workflow Canvas](screenshots/workflow-canvas.png)

## ✨ Features

- **Multi-Agent Architecture** – Specialized agents for research, outlining, content generation, and editing
- **Structured Output** – Uses Gemini + Vertex AI + output parsers for reliable JSON handling
- **Built-in Research** – Real-time data via integrated tools
- **Audience-Aware** – Adapts tone and content to any target audience
- **Email-Ready HTML** – Clean, formatted output with citations and sources section
- **Production Ready** – Max 1000 words to ensure high open rates
- **One-Click Import** – Full n8n workflow included

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **Google Vertex AI + Gemini 2.5 Flash** – LLM orchestration
- **Structured Output Parser** – Reliable JSON formatting
- **Gmail Node** – Automated delivery
- **Form Trigger** – Simple user input

## 📸 How It Works

1. Submit form → Topic, audience, tone
2. AI Agent creates table of contents
3. Split → Individual research agents generate each section
4. Merge → Professional editor assembles full newsletter
5. Final AI Agent creates subject line
6. Delivered to inbox

![Full Workflow](screenshots/workflow-canvas.png)

## 🚀 Quick Start

### Option 1: Import Ready-to-Use Workflow (Recommended)

1. Download 
2. Open n8n → **Import** → Upload the file
3. Connect your credentials:
   - Google Vertex AI
   - Google Gemini
   - Gmail (OAuth2)
4. Activate the workflow
5. Fill the form and watch it run!

### Option 2: Manual Setup

See [`docs/setup-guide.md`](docs/setup-guide.md)

## 📊 Sample Output

[View a real generated newsletter example](https://github.com/YOUR-USERNAME/multi-agent-seo-content-engine/blob/main/sample-newsletter.md)

## 🏗️ Architecture

Detailed breakdown available in [`docs/architecture.md`](docs/architecture.md)

## 🔮 Future Enhancements (Planned)

- Multi-language support
- LinkedIn & Twitter auto-posting
- Analytics dashboard
- Custom branding templates
- Scheduled newsletter runs

## 📬 Get In Touch

Built with ❤️ by **Shourya**  
Open to collaboration, feedback, or custom automation projects.

⭐ Star this repo if you find it useful!

---

**Made with n8n • Powered by multi-agent AI**
