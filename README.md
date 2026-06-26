```markdown
# 🔬 Agentic Deep Research Engine

An AI-powered Multi-Agent Research Assistant built using Python, Streamlit, and Google's Gemini API.

The system automatically creates a research plan, searches multiple information sources, extracts relevant evidence, ranks and verifies the collected information, and generates a downloadable research report.

---

## Features

- AI-based Research Planner Agent
- Automatic Research Sub-question Generation
- Wikipedia-based Information Retrieval
- Document Parsing
- Text Chunking
- Evidence Extraction
- Evidence Ranking
- Evidence Verification
- Automatic Markdown Report Generation
- Interactive Streamlit Web Interface

---

## Project Structure

```

deep_research_engine/
│
├── agents/
│   ├── planner_agent.py
│   ├── research_agent.py
│   ├── ranking_agent.py
│   ├── verifier_agent.py
│   └── report_agent.py
│
├── utils/
│   ├── web_search.py
│   ├── document_parser.py
│   ├── retriever.py
│   └── gemini_client.py
│
├── reports/
│   └── final_report.md
│
├── app.py
├── main.py
├── requirements.txt
├── README.md
└── .env

````

---

## Technologies Used

- Python
- Streamlit
- Google Gemini API
- Requests
- BeautifulSoup
- Markdown

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
````

Navigate to the project folder:

```bash
cd deep_research_engine
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Environment Setup

Create a `.env` file in the project root:

```
GEMINI_API_KEY=YOUR_API_KEY
```

---

## Run from Terminal

```bash
python main.py
```

---

## Run the Web Application

```bash
streamlit run app.py
```

---

## Output

The application generates:

* Research Plan
* Research Evidence
* Ranked & Verified Information
* Downloadable Markdown Report

The report is saved inside:

```
reports/final_report.md
```

---

## Research Workflow

1. User enters a research topic.
2. Planner Agent creates five research sub-questions.
3. Research Agent searches relevant Wikipedia pages.
4. Documents are downloaded and parsed.
5. Text is split into chunks.
6. Relevant chunks are retrieved.
7. Evidence is extracted.
8. Ranking Agent scores evidence.
9. Verifier Agent verifies evidence.
10. Report Agent generates the final research report.

---

## Author

Developed as an Agentic AI Research Engine project using Python, Streamlit, and Gemini API.

```
```
