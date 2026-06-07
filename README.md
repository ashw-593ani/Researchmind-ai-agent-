# ResearchMind AI Agent

This project is an **AI-powered Research Assistant** that uses **LangChain, Mistral AI, Tavily Search, and Web Scraping** to gather information from multiple sources, analyze it, and generate concise research summaries.

## Live Demo

The application is hosted and can be accessed here:

[ResearchMind AI Agent](https://researchmind123.streamlit.app/)

## Project Demo Video

Watch the complete project demonstration here:

[Project Demo Video](YOUR_GOOGLE_DRIVE_VIDEO_LINK)

## Features

The system provides the following capabilities:

| Feature           | Description                                            |
| ----------------- | ------------------------------------------------------ |
| Web Search        | Retrieves relevant information using Tavily Search API |
| Web Scraping      | Extracts content from websites using BeautifulSoup     |
| AI Research       | Analyzes gathered information using Mistral AI         |
| Summarization     | Generates concise research summaries                   |
| Context Awareness | Maintains context while answering queries              |
| Modular Design    | Easily extendable LangChain-based architecture         |

## Technologies Used

* **Python** – Programming Language
* **LangChain** – AI Agent Framework
* **Mistral AI** – Large Language Model
* **Tavily Search API** – Web Search Tool
* **BeautifulSoup** – Web Scraping
* **Requests** – HTTP Requests
* **Pandas** – Data Processing
* **Pydantic** – Data Validation
* **Rich** – Logging and CLI Output


## How to Use

1. Enter a research query.
2. The agent searches the web using Tavily.
3. Relevant webpages are scraped and processed.
4. Mistral AI analyzes the collected information.
5. A structured research summary is generated.

### Example Query

```text
Latest advancements in Generative AI
```

### Example Output

```text
Summary:
Generative AI has experienced rapid growth in multimodal models,
AI agents, enterprise adoption, and open-source ecosystems.
```

## Dependencies

```text
langchain
langchain-core
langchain-community
langchain-openai
langchain-mistralai
mistralai
tavily-python
beautifulsoup4
requests
lxml
python-dotenv
aiohttp
pandas
tiktoken
rich
tenacity
orjson
pydantic
html5lib
```

## File Structure

```text
├── app.py
├── agent.py
├── requirements.txt
├── .env
├── README.md
├── tools/
│   ├── search_tool.py
│   ├── scraper_tool.py
│   └── summary_tool.py
└── templates/
```

## Future Improvements

- PDF Upload & Research Support
- Research Report Export (PDF/DOCX)
- Multi-Agent Architecture
- Citation & Reference Generation
- Vector Database Integration (RAG)
- Research History Tracking
- User Authentication & Login System
- Chat History Management
- Source Credibility Scoring
- Voice-Based Research Assistant
- Multi-Language Support

