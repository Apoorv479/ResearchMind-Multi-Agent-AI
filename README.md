# ResearchMind – Multi-Agent AI Research System

ResearchMind is an AI-powered multi-agent research assistant that automates the complete research workflow using specialized AI agents.

The system performs web search, extracts detailed information from relevant sources, generates a structured research report, and finally critiques the report to improve its quality.

## Features

- Multi-agent architecture using LangChain
- AI-powered web search
- Automatic webpage scraping
- Structured research report generation
- AI-based report evaluation and feedback
- Interactive Streamlit interface
- Modular and extensible architecture

## Architecture

User Query
      │
      ▼
Search Agent
      │
      ▼
Reader Agent
      │
      ▼
Writer Chain
      │
      ▼
Critic Chain
      │
      ▼
Final Research Report

## Tech Stack

- Python
- LangChain
- OpenAI GPT-4o Mini
- Tavily Search API
- BeautifulSoup
- Requests
- Streamlit
- Pydantic
- dotenv

## Project Structure

```
ResearchMind/
│
├── app.py
├── agents.py
├── pipeline.py
├── tools.py
├── requirements.txt
└── README.md
```

## Workflow

### 1. Search Agent
Searches the web for reliable and recent information.

### 2. Reader Agent
Selects the most relevant source and extracts meaningful content.

### 3. Writer Chain
Generates a detailed research report including:
- Introduction
- Key Findings
- Conclusion
- Sources

### 4. Critic Chain
Reviews the generated report and provides:
- Quality score
- Strengths
- Areas for improvement
- Final verdict

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/ResearchMind-Multi-Agent-AI.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
OPENAI_API_KEY=your_openai_api_key
TAVILY_API_KEY=your_tavily_api_key
```

Run the Streamlit application

```bash
streamlit run app.py
```

## Example

Input

```
Quantum Computing Breakthroughs in 2025
```

Output

- Relevant web sources
- Scraped content
- Comprehensive research report
- AI-generated critique

## Future Improvements

- Multi-source document synthesis
- PDF report export
- Citation management
- Vector database integration
- Retrieval-Augmented Generation (RAG)
- Memory-enabled research agents
- Human-in-the-loop review

## Skills Demonstrated

- Multi-Agent AI Systems
- LLM Application Development
- Prompt Engineering
- LangChain
- AI Workflow Design
- Web Scraping
- Streamlit
- Python
- API Integration
- Modular Software Architecture

## Author

Apoorv Jha
