# 🔬 ResearchMind

### Multi-Agent Intelligence for Deep Research

ResearchMind is an AI-powered Multi-Agent Research System that automates the complete research workflow using specialized AI agents. The system searches the web, extracts relevant information, generates structured research reports, critiques its own output, and allows exporting reports in Markdown and PDF formats.

---

## 🚀 Features

* 🔍 Search Agent for web research
* 📄 Reader Agent for content extraction
* ✍️ Writer Chain for report generation
* 🧐 Critic Chain for report evaluation
* 📥 Export reports as Markdown and PDF
* 🎨 Modern Streamlit-based UI
* 🌐 Real-time web research using Tavily
* 🤖 Powered by Mistral AI and LangChain

---

## 🏗️ System Architecture

```text
User Query
     │
     ▼
┌─────────────────┐
│  Search Agent   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Reader Agent   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Writer Chain   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│  Critic Chain   │
└────────┬────────┘
         │
         ▼
 Final Research Report
```

---

## 📂 Project Structure

```text
RESEARCHMIND/
│
├── app.py              # Streamlit frontend
├── agents.py           # Agent definitions and chains
├── tools.py            # Search and scraping tools
├── pipeline.py         # Research workflow pipeline
├── requirements.txt    # Project dependencies
├── .env                # API keys
├── .gitignore
│
├── __pycache__/
│
└── .venv/
```

---

## ⚙️ Tech Stack

### AI & Agents

* LangChain
* Mistral AI
* LCEL (Runnable Pipelines)

### Research Tools

* Tavily Search API
* BeautifulSoup
* Requests

### Frontend

* Streamlit

### Report Generation

* ReportLab

### Utilities

* Python Dotenv
* Rich

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/researchmind.git

cd researchmind
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
TAVILY_API_KEY=your_tavily_api_key
MISTRAL_API_KEY=your_mistral_api_key
```

> Never commit your `.env` file to GitHub.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will launch at:

```text
http://localhost:8501
```

---

## 📝 Example Research Topics

* Autonomous AI Agents
* Artificial General Intelligence (AGI)
* Quantum Computing Breakthroughs
* Nuclear Fusion Energy
* Future of Human-AI Collaboration
* CRISPR & Human Enhancement
* Impact of Geopolitical Conflicts on Global Economy

---

## 🚧 Future Improvements

* LangGraph Integration
* Multi-Source Research
* Citation Management
* Memory Support
* Agent-to-Agent Communication
* Vector Database Integration
* Research History Dashboard



---

## 👨‍💻 Author

**Amit Kumar Rana**

AI Engineer | Machine Learning Enthusiast | Agentic AI Builder

---

## ⭐ Support

If you found this project useful:

* ⭐ Star the repository
* 🍴 Fork the project
* 🚀 Share your feedback

---

### ResearchMind

**"Multi-Agent Intelligence for Deep Research."**

Built with ❤️ by Amit Kumar Rana
