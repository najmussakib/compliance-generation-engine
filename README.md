### Objective

This project establishes an automated Video Compliance QA Pipeline orchestrated by LangGraph, designed to audit content against regulatory standards using a RAG architecture.

- We leverage `Azure Video Indexer` for multimodal ingestion (transcripts/OCR).

- `Azure AI Search` to retrieve relevant compliance rules via Azure OpenAI Embeddings.

- The core reasoning engine, `Azure OpenAI (GPT-4o)`, synthesizes this data to deterministically detect violations.

- `LangSmith` provides granular tracing for LLM workflow optimization.

- `Azure Application Insights` is integrated for production-grade telemetry, logging, and real-time performance monitoring.

    This end-to-end system transforms unstructured video into structured, actionable JSON compliance reports with deep full-stack observability.

### Architecture
