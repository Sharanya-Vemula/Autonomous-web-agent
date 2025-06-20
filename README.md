# 🧠 AI Agent Builder – Autonomous Browser Automation

This project is a custom implementation of an **AI-powered agent system** capable of performing browser tasks **autonomously**, without human intervention. The system uses [browser-use](https://github.com/browser-use/browser-use) as the backend and [web-ui](https://github.com/browser-use/web-ui) for a powerful front-end interface, allowing users to define and control intelligent agents that interact with the browser through natural language.

---

## 🚀 Project Overview

- **Name**: AI Agent Builder
- **Type**: Autonomous AI Agent Platform
- **Purpose**: Enable AI agents to perform browser tasks (like searching, clicking, form-filling, navigating, etc.) without human assistance
- **Interface**: Local Web UI powered by `web-ui`
- **Backend Engine**: `browser-use` with support for agent scripts, browser commands, and execution logic

---

## 🌐 Demo Screenshot

![Web UI Screenshot] ![Interface](https://github.com/user-attachments/assets/5b616865-7861-4921-868c-36682bbe135c)
![Screenshot 2025-06-20 140705](https://github.com/user-attachments/assets/005ca02a-153f-46b9-8384-2ce343562c62)
![Screenshot 2025-06-20 140819](https://github.com/user-attachments/assets/9c3ed042-ce3a-4798-8ae4-b33ce7bd0f06)

> *Control your browser with AI assistance — Agent Settings, Browser Controls, Execution, and More*

---

## 🧩 Features

- 🔧 **Agent Configuration Panel** – Define and manage system prompts
- 🌍 **Browser Environment Control** – Control browsing context, sandboxing, and agent execution
- 🤖 **Run Agent** – Execute predefined or custom autonomous agents
- 🛒 **Agent Marketplace** – Explore additional community agents
- 🌑 **Dark Mode Support** – Developer-friendly interface with theme options

---

## 🛠️ Tech Stack

| Layer         | Tech                      |
|--------------|---------------------------|
| Frontend     | [web-ui](https://github.com/browser-use/web-ui) |
| Backend      | [browser-use](https://github.com/browser-use/browser-use) |
| Language     | Python, JavaScript        |
| Browser Base | Chromium (via Playwright) |
| Deployment   | Localhost (via `webui.py`) |

---

## 📦 Installation & Setup

### Prerequisites

- Python 3.9+
- Node.js (for UI if modifying)
- Chromium (automatically handled by Playwright)

### Step-by-Step

1. **Clone both repositories**
   ```bash
   git clone https://github.com/browser-use/browser-use
   git clone https://github.com/browser-use/web-ui

2. **Set up the backend (browser-use)**
   cd browser-use
   pip install -e .
   playwright install chromium

3. **Run the Web UI**
   cd ../web-ui
   python webui.py --ip 127.0.0.1 --port 7788

4. **Access the platform**
   Open browser: http://127.0.0.1:7788

   
## 🖼️ AI Agent Demo (GIF)
   ![7a5cf69e-c475-4a34-bf90-43c3a5798db4](https://github.com/user-attachments/assets/02401aa2-595c-4112-a4da-b209a1386efa)


## 🔍 Use Cases
Automated web form submission

Data scraping and summarization

AI-powered shopping bots

Research agents

Testing automation without scripting


