# 🏙️ City Assistant Agent

An AI-powered City Assistant Agent built with Python and Streamlit to provide an interactive interface for city-related assistance. The project demonstrates how Generative AI and AI agents can be used to build helpful, conversational applications.

🚀 **Live Demo:** [Try City Assistant Agent](https://city-assistant-agent-h8z762cjudxqw97kgohu2b.streamlit.app/)

## ✨ Features

* 🤖 **AI-Powered Assistance** — Interact with an AI assistant through a simple interface.
* 💬 **Interactive Experience** — Ask questions and receive AI-generated responses.
* 🌐 **Web-Based Application** — Access the application directly through your browser.
* 🐍 **Python-Based Development** — Built using the Python ecosystem.
* ☁️ **Cloud Deployment** — Deployed using Streamlit Community Cloud.

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Frontend:** Streamlit
* **AI/LLM Integration:** Depends on the model and provider configured in the project
* **Deployment:** Streamlit Community Cloud
* **Version Control:** Git and GitHub

## 🌐 Live Application

Visit the deployed application:

👉 https://city-assistant-agent-h8z762cjudxqw97kgohu2b.streamlit.app/

## 📂 Project Structure

```text
city-assistant-agent/
├── city_agent_app.py
├── Agents.py
├── toolcalling.py
├── owntrol.py
├── newssummarizer.py
├── requirements.txt
└── .gitignore
```

*Note: Update this structure if your repository contains additional files or folders.*

## ⚙️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/amar9198/city-assistant-agent.git
cd city-assistant-agent
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root and add the API keys required by your application.

```env
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
```

Replace these example variables with the exact keys your code uses. Obtain credentials from the relevant providers, and never commit real API keys to GitHub.

### 5. Start the application

```bash
streamlit run city_agent_app.py
```

Open the local URL displayed in your terminal, usually `http://localhost:8501`.

## 🔐 Security

* Keep API keys and credentials private.
* Store secrets in `.env` locally or in Streamlit Cloud's Secrets settings.
* Ensure `.env` is listed in `.gitignore`.
* Never publish private credentials in source code or repository commits.

## 🎯 Project Goal

The goal of this project is to explore practical applications of Generative AI, AI agents, and interactive web applications using Python.

## 🚀 Future Improvements

* Add more city-related tools and capabilities.
* Improve conversation handling and user experience.
* Integrate additional APIs and data sources.
* Enhance error handling and response reliability.
* Expand the assistant's capabilities based on user needs.

## 👨‍💻 Author

**Amar**

* GitHub: [@amar9198](https://github.com/amar9198)
* Project Repository: [city-assistant-agent](https://github.com/amar9198/city-assistant-agent)

---

⭐ If you find this project interesting, consider giving the repository a star!

*Built with Python, AI, and a passion for learning.*
