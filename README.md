# Multi Agent Research System

## Overview

Multi Agent Research System is an AI-powered research assistant built using LangChain and a multi-agent architecture. The system automates the complete research workflow by combining specialized agents that search, analyze, summarize, and critique information before generating a structured research report.

## Features

* Multi-agent pipeline architecture
* Live web search and information retrieval
* Deep content extraction from web pages
* Automated report generation
* AI-powered quality review and scoring
* Shared state management between agents
* Interactive Streamlit user interface
* Modular and scalable project structure

## Architecture

The system consists of multiple specialized agents:

### Search Agent

Retrieves relevant and up-to-date information from the web.

### Reader Agent

Extracts and processes detailed content from selected sources.

### Writer Agent

Generates comprehensive and structured research reports.

### Critic Agent

Reviews generated reports and provides feedback for quality improvement.

## Tech Stack

* Python
* LangChain
* OpenAI API
* Streamlit
* BeautifulSoup
* Requests

## Installation

```bash
git clone <your-repository-url>
cd multi-agent-research-system
pip install -r requirements.txt
```

## Usage

```bash
streamlit run app.py
```

Enter a research topic, and the system will automatically:

1. Search for relevant information
2. Read and analyze sources
3. Generate a detailed report
4. Critique and evaluate the output

## License

This project is open-source and available under the MIT License.
