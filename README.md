# Langgraph-Blog-Writer
AI-powered blog writing system using LangGraph. Automatically plans, researches, writes, cites, and illustrates technical blog posts via a multi-agent workflow with a Streamlit UI. Supports live progress, image generation, and export-ready Markdown


# Blog Writing Agent (LangGraph)

An end-to-end AI blog generation system built with LangGraph and Streamlit.  
It plans, researches, writes, cites, and illustrates technical blog posts using a multi-agent workflow.

## ✨ Features
- Intelligent routing (closed-book, hybrid, open-book)
- Automated web research with citations
- Multi-section blog planning and parallel writing
- Optional code generation per section
- Automatic technical diagrams with image placement
- Streamlit UI with live progress, logs, and exports

## 🧠 Architecture
Router → Research → Planner → Parallel Writers → Reducer → Image Generator

## 🛠 Tech Stack
- LangGraph
- LangChain
- OpenAI / Gemini
- Tavily Search
- Streamlit
- Pydantic

## 🚀 Getting Started
```bash
pip install -r requirements.txt
streamlit run bwa_frontend.py
