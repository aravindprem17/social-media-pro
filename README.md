🤖 Social Media Pro: Private Multi-Agent AI Team
An autonomous content engine with a web interface, running 100% locally on Apple Silicon.

🌟 Overview
Social Media Pro is a multi-agent system that automates the transition from "idea" to "viral post." Unlike standard AI tools that rely on cloud APIs, this project uses a local Gemma 3 1B model to perform complex reasoning, ensuring 100% data privacy and zero cost per run.

This version features a Streamlit Web Interface, allowing you to generate content through a professional GUI instead of the terminal.

🖥️ Interactive Web Interface
The project includes a built-in web app that allows you to:

Toggle Models: Switch between gemma3:1b (Fast) and llama3.1:latest (Deep) via the sidebar.

Real-time Progress: Track agent "thoughts" and status through Streamlit's status containers.

Instant Export: Download your generated LinkedIn posts as .txt files with one click.

🧠 The Team (Multi-Agent Architecture)
Senior Social Media Strategist: Analyzes the topic using digital psychology to find viral "hooks."

Lead Content Creator: Transforms the strategy into a formatted, high-engagement LinkedIn post.

🛠️ Tech Stack
Orchestration: CrewAI

Web UI: Streamlit

Local LLM: Ollama

Environment Manager: uv
📦 Installation & Setup
1. Prerequisites
Install Ollama

Pull the models:

ollama pull gemma3:1b
ollama pull llama3.1:latest

2. Clone and Install

git clone https://github.com/[YOUR_GITHUB_USERNAME]/social-media-pro.git
cd social-media-pro

# Install dependencies including Streamlit using uv
uv sync

3. Run the Application
You can now run the project in two ways:

Option A: Web Interface (Recommended)

uv run streamlit run app.py

Option B: Terminal Mode

uv run main.py

📂 Project Structure

social-media-pro/
├── config/
│   ├── agents.yaml      # Agent roles and backstories
│   └── tasks.yaml       # Task definitions
├── app.py               # Streamlit Web Interface
├── main.py              # CLI execution logic
├── pyproject.toml       # Dependency management (Streamlit, CrewAI, etc.)
└── README.md            # Project documentation



Developed by Aravind Prem https://www.linkedin.com/in/aravindprem/
