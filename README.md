AEC AI Assistant

Overview: A digital assistant for the Architecture, Engineering, and Construction (AEC) domain that answers natural-language questions about codes and specifications and returns concise facts and summaries. The system combines retrieval and generation (RAFT: RAG + fine-tuning) to improve factuality and domain relevance, and includes a simple chatbot UI that preserves conversation history.

Features:

- Retrieval-augmented generation with a RAFT architecture (RAG + fine-tune).

- Automated evaluation pipeline using ROUGE and cosine similarity to compare model outputs with references.

- Experimental results: RAFT outperformed RAG-only, fine-tune-only, and the base Mistral model by ~10% under our evaluation scheme (see Project Report).

- Web/chat UI with conversation history - the assistant can answer follow-up questions in context.

- Document ingestion and retriever indexing for corpora of codes/specs.

Evaluation: The evaluation pipeline computes F-value using different ROUGE scores and embedding-based cosine similarity between model outputs and references, and produces comparative performance reports across model variants.

Please refer to the project paper for more details.
