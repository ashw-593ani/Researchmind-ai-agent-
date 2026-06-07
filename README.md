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

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repo-url>
cd ResearchMind-AI-Agent
```

### 2. Create a Virtual Environment

```bash
python -m venv myenv
```

### Activate the Environment


```bash
myenv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Create a .env File

```env
MISTRAL_API_KEY=your_mistral_api_key
TAVILY_API_KEY=your_tavily_api_key
```

### 5. Run the Application

```bash
python app.py
```

### 6. Access the Application

```text
Local URL:
http://127.0.0.1:5000/

Hosted URL:
YOUR_DEPLOYMENT_LINK
```

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

