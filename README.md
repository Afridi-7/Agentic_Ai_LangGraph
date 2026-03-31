# 🚀 Agentic AI with LangGraph

A hands-on collection of **agentic AI systems built from scratch using LangGraph, LangChain, and LLMs** — focused on real workflows, not just chat demos.

This repository explores how to design **stateful, tool-using, decision-making AI agents** that go beyond simple prompt-response patterns.

---

## 🧠 What This Project Is About

Most AI projects stop at:
input → LLM → output

This project focuses on:
input → reasoning → tool usage → memory → iteration → outcome

Built using **LangGraph**, which enables:

* Stateful workflows
* Multi-step reasoning
* Tool calling
* Conditional execution
* Agent loops

---

## ⚙️ Features

* Modular agent architecture (nodes + edges)
* Looping workflows with decision logic
* Tool calling (math, document editing, etc.)
* Memory-aware conversations
* Document editing agent (update + save)
* Streamlit frontend integration
* Multi-turn interaction support

---

## 🏗️ Architecture

User Input
↓
Agent (LLM reasoning)
↓
Tool Decision
↓
Tool Execution
↓
State Update (Memory)
↓
Repeat / Exit

This follows the **agentic loop pattern**, where the model decides what to do, acts using tools, updates state, and continues until completion.

---

## 📂 Project Structure

Agentic_Ai_LangGraph/
│
├── Agents/              # Core agent implementations
├── app.py               # Streamlit frontend
├── agent.py             # Main agent logic
├── tools.py             # Custom tools (update, save, etc.)
├── requirements.txt
└── README.md

---

## 🛠️ Tech Stack

* LangGraph → Workflow orchestration
* LangChain → LLM abstraction
* OpenAI / Gemini → LLM backend
* Streamlit → Frontend UI
* Python → Core logic

---

## 🚀 Getting Started

1. Clone the repo

git clone https://github.com/Afridi-7/Agentic_Ai_LangGraph.git
cd Agentic_Ai_LangGraph

2. Create environment

python -m venv venv
venv\Scripts\activate

3. Install dependencies

pip install -r requirements.txt

4. Set environment variables

Create a `.env` file with:

OPENAI_API_KEY=your_api_key_here

5. Run Streamlit app

streamlit run app.py

---

## 💡 Example Use Case

Document Editing Agent

* Update content dynamically
* Maintain internal state
* Save final output to file

Example interaction:

User: Write an introduction about AI
Agent: updates document

User: Add a section on machine learning
Agent: modifies document

User: Save as report.txt
Agent: writes file and exits

---

## 🧪 What You’ll Learn

* How to build agents from scratch
* Difference between LLMs vs agent systems
* Designing tool-driven workflows
* Managing state and memory
* Creating looping decision systems

---

## ⚠️ Important Notes

* Requires API keys (OpenAI / Gemini)
* Works best on Python 3.10–3.12 (LangChain issues on 3.14)
* Tool-calling reliability depends on model used

---

## 📈 Future Improvements

* RAG integration (retrieval-based agents)
* Multi-agent collaboration
* Persistent memory (DB-backed)
* Better UI/UX for agent interaction

---

## 🤝 Contributing

Contributions are welcome.
If you’re experimenting with agent systems, feel free to extend or improve workflows.

---

## ⭐ Why This Project Matters

This is not just another chatbot.

It demonstrates how AI systems move from passive responses → active decision-making agents.

---

## 📌 Author

Afridi

Exploring:

* Agentic AI
* Systems Design
* Real-world LLM applications

---

## 📜 License

MIT License
