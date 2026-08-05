# `RAG` Basics

**RAG-Basics** is a compact yet practical repository designed to provide a strong foundation for learning and experimenting with Retrieval-Augmented Generation (RAG) workflows. It combines hands-on Jupyter notebooks, lightweight source modules, and diverse datasets to help users understand both basic and advanced RAG patterns.
<br>

The repository includes multiple notebooks:
- `typesense.ipynb` demonstrates search and retrieval using a Typesense-backed setup.
- `RAGfromScratch.ipynb` walks step by step through building a basic RAG pipeline, covering document ingestion, chunking, embedding, vector storage, and retrieval.
- `agenticRAGwithLangGraph.ipynb` introduces an agentic RAG architecture using LangGraph, showcasing how LLM-driven agents can orchestrate multi-step reasoning over retrieved documents. This notebook demonstrates stateful graph-based workflows, tool usage, conditional execution, and iterative decision-making on top of a FAISS vector store—illustrating how RAG systems can move beyond simple retrieve-and-generate patterns into more autonomous, controllable pipelines.
<br>

In addition to notebooks, the repository contains:
- A lightweight `src/` module for extensibility and experimentation.
- A `data/` directory with diverse data formats, including PDFs (attention.pdf, YOLO.pdf), text files (python_intro.txt, ML_intro.txt), and a persisted Chroma vector store (chroma.sqlite3 and supporting binary files) to demonstrate indexing and retrieval.
- `books.jsonl` as a structured dataset for retrieval experiments.
- `test.txt` for quick embedding and similarity-search tests.
- `requirements.txt` to enable seamless environment setup.
<br>

Together, these assets form a self-contained RAG experimentation ecosystem, allowing users to explore ingestion of heterogeneous data sources, experiment with multiple vector stores and retrieval strategies, and build both traditional and agentic end-to-end RAG pipelines directly from the notebooks.
