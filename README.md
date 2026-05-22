First AI Agent using Google ADK
Welcome to the First AI Agent using ADK repository! This project is a hands-on, notebook-driven guide designed to document and demonstrate how to develop intelligent AI agents using Google's Agent Development Kit (ADK).

Instead of raw scripts, this repo leverages interactive Jupyter Notebooks to break down core agentic concepts visually and step-by-step.

🚀 Overview
The Agent Development Kit (ADK) is an open-source framework by Google built to design, debug, and deploy reliable AI agents at scale. This repository tracks my journey of mastering ADK—moving from basic single-agent prompts to complex multi-agent orchestration, tool usage, and durable state management.

🧠 Key Concepts Covered
The Jupyter Notebooks in this repo cover the three foundational pillars of ADK:

Agent: Defining the "brain" via prompt instructions, selecting LLM backends (like Gemini), and scoping their specific mission.

Session: Implementing the memory layer to handle conversation history and persistent state, allowing long-running agent interactions.

Runner: Understanding the orchestration engine that executes the input-reason-action loop.

⚙️ Getting Started
Follow these terminal commands to set up the project locally and run the notebooks.

1. Clone the Repository
Bash
git clone https://github.com/4nkit-3isGGS/first-ai-agent-using-adk.git
cd first-ai-agent-using-adk
2. Set Up a Virtual Environment
Bash
python -m venv venv
source venv/bin/activate
Note for Windows users: Use venv\Scripts\activate instead.

3. Install Dependencies
Bash
pip install -r requirements.txt
4. Configure Environment Variables
Create a .env file in the root directory and add your Google AI Studio API key:

Code snippet
GOOGLE_API_KEY=your_actual_api_key_here
📓 Launching the Notebooks
Once everything is installed, fire up Jupyter to start exploring the code:

Bash
jupyter notebook
Select any .ipynb file from the dashboard, run the cells sequentially using Shift + Enter, and start experimenting with the ADK framework!

Created and maintained by 4nkit-3isGGS. Feel free to star the repo if you find these ADK tutorials helpful!
