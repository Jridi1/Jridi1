# Abderrahim Jridi

AI Engineer. I build AI agents and RAG systems, and Power BI dashboards for data analysis.

Master's in Data and AI (Université Catholique de Lille), engineering degree in statistics and information analysis (ESSAI, Tunis).

## About

I build AI agents and LLM applications, and I care about getting them to actually run. I deployed an NLP system in production at Zitouna Bank using Django, and today I work on RAG and agentic architectures.

On the analytics side, I build Power BI dashboards that turn raw data into something a team can use to make decisions.

My approach is simple: understand the business problem first, pick the tools second, then ship something people actually use.

I'm happy to talk about AI engineering roles.
<!--
## Current project

**[DocMind](LINK_TO_DOCMIND)**, a RAG assistant over a document base.

Document ingestion and chunking, local embeddings (sentence-transformers), FAISS retrieval, generation through Groq (Llama 3.1), Gradio interface. I built it end to end to put the IBM RAG and Agentic AI certification into practice.
-->
<!--
## AI agents

Add one agent project here: what it does, what tools it uses, link.
-->

<!--
## Power BI

Add one dashboard project here: the dataset, the question it answers, link or screenshot.
-->

## AI agents

**Current project**

**[CSV Data Analyst Agent](https://github.com/Jridi1/data-analysis-agent)**, a data analysis agent whose model written Python runs in a locked down Docker sandbox.
The LLM (Groq) writes the code, and the sandbox runs it with no network, no secrets, read only files and limits on time, memory and output. I built it after a test showed that the standard LangChain pandas agent exposes API keys. It comes with an attack test suite and a full fraud analysis under temporal drift (PR-AUC 0.37 on a sealed test set).

## Experience

- **Zitouna Bank**: NLP system deployed in production, Django backend.
- **Enedis**: work-study (alternance).
- **Factory Of The Sol**: early-stage startup.

## Stack

| Area | Tools |
| --- | --- |
| AI and agents | Python, LangChain, FAISS, Groq, sentence-transformers, Gradio |
| Data and analytics | Power BI, SQL, Pandas, NumPy, MongoDB |
| Backend and web | FastAPI, Django, JavaScript |
| Tools | Docker, Git |

## Education and certifications

- IBM RAG and Agentic AI Professional Certificate (IBM, Coursera)
- Data Science certifications (DataCamp)
- Master's in Data and AI, Université Catholique de Lille
- Engineering degree, ESSAI (Tunis)

## Contact

- Email: [jeridi.abderrahim@gmail.com](mailto:jeridi.abderrahim@gmail.com)
- LinkedIn: [linkedin.com/in/abderrahim-jridi](https://www.linkedin.com/in/abderrahim-jridi)
