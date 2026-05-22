First AI Agent using Google ADK
Welcome to the First AI Agent using ADK repository! This project is a hands-on, notebook-driven guide designed to document and demonstrate how to develop intelligent AI agents using Google's Agent Development Kit (ADK).

Instead of raw scripts, this repo leverages interactive notebooks to break down core agentic concepts visually and step-by-step.

🚀 Overview
The Agent Development Kit (ADK) is an open-source framework by Google built to design, debug, and deploy reliable AI agents at scale. This repository tracks my journey of mastering ADK—moving from basic single-agent prompts to complex multi-agent orchestration, tool usage, and durable state management.

🧠 Key Concepts Covered
The Jupyter Notebooks in this repo cover the three foundational pillars of ADK:

Agent: Defining the "brain" via prompt instructions, selecting LLM backends (like Gemini), and scoping their specific mission.

Session: Implementing the memory layer to handle conversation history and persistent state, allowing long-running agent interactions.

Runner: Understanding the orchestration engine that executes the input-reason-action loop.

📁 Repository Structure & Notebooks
Plaintext
├── first_ai_agent.ipynb         # Setting up ADK, API keys, and your first conversational agent
├── Multi_agent_workflow.ipynb   # Hand-offs and coordination between specialized agents                 y
└── requirements.txt             # Project dependencies (ADK, Jupyter, etc.)

⚙️ Getting Started
To run these notebooks locally and interact with the code, follow these steps:

Prerequisites
Python 3.11 or higher

A Google API Key (Get one via Google AI Studio)

Setup & Installation
Clone the repository:

git clone https://github.com/4nkit-3isGGS/first-ai-agent-using-adk.git
cd first-ai-agent-using-adk


2. **Create and activate a virtual environment:**
   ```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
This will install the google-adk, notebook (or jlab), and other required helper libraries.

pip install -r requirements.txt


4. **Configure your environment variables:**
   Duplicate the `.env.example` file, rename it to `.env`, and add your API key:
   ```env
GOOGLE_API_KEY=your_actual_api_key_here
📓 How to Use the Notebooks
Launch Jupyter Notebook or JupyterLab from your terminal:

Bash
jupyter notebook
Open the first notebook (e.g., first_ai_agent.ipynb).

Run the cells sequentially (Shift + Enter).

Experiment by modifying the agent's instructions or adding new tools to see how the ADK engine adapts!

Created and maintained by 4nkit-3isGGS. Feel free to star the repo if you find these ADK tutorials helpful!
