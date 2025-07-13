#  Multi-Agent System using LangGraph 

This project demonstrates a modular **multi-agent system** built using [LangGraph](https://github.com/langchain-ai/langgraph), powered entirely by **free and open tools** 

The system simulates how multiple AI agents can **collaborate** to solve a real-world problem, such as analyzing the **impact of electric vehicles in India by 2030**, using tools like web search, logic analysis, and report writing.

---

## 🔧 Tech Stack

| Component         | Tool Used                          | Free |
|------------------|-------------------------------------|------|
| LLM              | `google/flan-t5-base` (HuggingFace) | ✅   |
| Orchestration    | LangGraph                           | ✅   |
| Tooling          | SerpAPI (web search)                | ✅ (with free key) |
| Analysis Tool    | Python REPL Tool                    | ✅   |
| Summarization    | Transformers pipeline               | ✅   |

---

##  Features

-  No OpenAI or paid APIs
-  Uses free HuggingFace LLMs
-  Web search via SerpAPI (100 free queries/month)
-  Python REPL for numeric/logical reasoning
-  Final report generated via LLM
-  Fully modular multi-agent graph using LangGraph

---

## Project Structure

---

##  How It Works

###  Agents

1. **🔍 Research Agent**  
   Takes the user query and uses SerpAPI to fetch relevant web content.

2. **📊 Analyst Agent**  
   Analyzes the research using logical reasoning via a REPL tool and summarizes the insights using an LLM.

3. **📝 Writer Agent**  
   Generates a concise report from the research and analysis using a free HuggingFace model.

---

##  Setup Instructions

### 1. Clone the Repository

git clone https://github.com/yourusername/multi-agent-langgraph.git
cd multi-agent-langgraph

### 2. Install Required Dependencies

If you're using **Google Colab**, copy and paste this into the first code cell:

pip install -U langgraph langchain langchain-community langchain-experimental \
transformers google-search-results python-dotenv

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add new tools, agents, or improve workflows, feel free to open an issue or pull request. Let’s build better multi-agent systems together!

---

##  Author & Credits

This project was created by **Nikita Sharma** as part of the **Week 8 – Multi-Agent Systems** hands-on assignment.

### 🛠️ Contributions:
- Designed and implemented a modular multi-agent workflow using LangGraph
- Integrated free LLMs from HuggingFace
- Connected SerpAPI for research capabilities
- Built reusable agents for analysis and report generation
- Documented the entire system with code and markdown instructions

> Made with 💻 + ☕ + 🧠 for learning and collaboration.

---

