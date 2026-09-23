<h1 align="center">Tejas Sinroja</h1>

<p align="center">
  <b>AI Engineer</b> · agentic AI systems, LLM applications and developer tools
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tejas-sinroja/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-tejas--sinroja-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="https://pypi.org/project/vestrix/"><img alt="Vestrix on PyPI" src="https://img.shields.io/pypi/v/vestrix?label=vestrix%20on%20PyPI&color=ea580c"></a>
</p>

I'm an AI engineer at **Accely**. I build agentic AI systems and LLM-powered applications, plus the tools developers
need to understand them. My work covers multi-agent RAG, computer vision and MLOps, and I take projects from notebook
experiments to tested, versioned and released software.

---

## Featured: Vestrix

<a href="https://github.com/Tejas-Sinroja/Vestrix">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Tejas-Sinroja/Vestrix/main/docs/brand/logo-dark.svg">
    <img alt="Vestrix" src="https://raw.githubusercontent.com/Tejas-Sinroja/Vestrix/main/docs/brand/logo-light.svg" width="260">
  </picture>
</a>

**AI wrote it. See how it flows.** Vestrix is an interactive call-graph and data-flow explorer for Python. You point it
at any codebase to see what an HTTP route actually runs, trace a value across every function it touches, and catch
circular imports before they crash, all without running the code.

```bash
pip install vestrix
vestrix ui
```

- Whole-program value tracing, call graphs and module maps in an offline web app
- Detects entry points (FastAPI/Flask routes, scripts, CLI commands, tasks, tests) and the frameworks a project uses
- Finds circular imports and fails CI on import-time cycles
- Zero dependencies, published on PyPI with automated, tested releases

[Repository](https://github.com/Tejas-Sinroja/Vestrix) · [PyPI](https://pypi.org/project/vestrix/) · [Changelog](https://github.com/Tejas-Sinroja/Vestrix/blob/main/CHANGELOG.md)

<img alt="Vestrix tracing a request body across functions" src="https://raw.githubusercontent.com/Tejas-Sinroja/Vestrix/main/docs/images/trace.png" width="100%">

---

## Selected projects

### Agentic AI and LLM applications

| Project | What it does | Built with |
|---|---|---|
| [Academic AI Assistant](https://github.com/Tejas-Sinroja/Academic-Ai-Assistant) | Multi-agent assistant for students: turns course material into study notes, plans schedules, gives personalised advice and answers questions over PDFs and notes | LangChain, RAG, multi-agent |
| [Blog Post Generator](https://github.com/Tejas-Sinroja/Blog_Post_generator) | Agent that researches a topic on the web and writes a blog post about it | Google ADK, LangChain, DuckDuckGo, Gemini via LiteLLM |
| [GenAI Project Template](https://github.com/Tejas-Sinroja/GenAI_Project_template) | Starter kit for LLM apps: GPT and Claude clients, prompt tooling, rate limiting, caching and token counting | Python, OpenAI, Anthropic |
| [Voice Assistant](https://github.com/Tejas-Sinroja/Voice_Assistant) | Record or upload audio and ask questions about what was said | Whisper, GPT-4o-mini, Streamlit |

### Computer vision and deep learning

| Project | What it does | Built with |
|---|---|---|
| [Kidney Disease Classification](https://github.com/Tejas-Sinroja/Kidney-Diseas-Classification) | End-to-end pipeline that classifies kidney CT scans, with experiment tracking and data versioning | CNN, MLflow, DVC |
| [Vehicle Counting and Speed Estimation](https://github.com/Tejas-Sinroja/vehicle-counting-and-speed-estimation) | Detects, tracks, counts and estimates the speed of vehicles in traffic video | YOLOv8, OpenCV |
| [Visual Insight Assistant](https://github.com/Tejas-Sinroja/VIA-Visual-Insight-Assistant) | Recognises food from a photo and returns nutritional insights ([live demo](https://visual-insight-assistant.streamlit.app/)) | Computer vision, Streamlit |

### Machine learning

[Book recommendation](https://github.com/Tejas-Sinroja/Book_Recommendation_System) · [Credit card fraud detection](https://github.com/Tejas-Sinroja/credit-card-fraud-detection-system) · [Spam SMS detection](https://github.com/Tejas-Sinroja/spam-sms-detection) · [Email spam detection](https://github.com/Tejas-Sinroja/Email-spam-detection) · [Movie genre classification](https://github.com/Tejas-Sinroja/movie-genre-classification) · [Car price prediction](https://github.com/Tejas-Sinroja/Car-price-predicion)

---

## Tech stack

| | |
|---|---|
| **Languages** | Python · C++ |
| **LLMs and agents** | LangChain · LangGraph · Google ADK · CrewAI · AutoGen · Agno · OpenAI · Anthropic Claude · MCP |
| **ML and vision** | PyTorch · TensorFlow · OpenCV · YOLOv8 · Pandas · NumPy |
| **Apps and APIs** | FastAPI · Flask · Streamlit |
| **MLOps and tooling** | MLflow · DVC · GitHub Actions · PyPI packaging · Jupyter |

---

## Currently

- Building **[Vestrix](https://github.com/Tejas-Sinroja/Vestrix)**. Next up is a runtime overlay that shows what
  actually ran during your tests, drawn on top of the static graph.
- Designing agentic AI systems and the evaluation and tooling that make them dependable.

## Connect

I'm happy to talk about agentic AI, developer tooling or collaboration. Reach me on
**[LinkedIn](https://www.linkedin.com/in/tejas-sinroja/)**.
