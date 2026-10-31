# finance-rag
Question answering over public bank and insurance documents, in French and English, with page-level citations.

## Goal
Answer questions on annual reports and product terms reliably: grounded answers, cited pages, measured quality, no made-up facts.

## Data
Public documents from French banks and insurers (e.g. Universal Registration Documents, product terms). Public sources only.

## Planned architecture
PDF parsing -> chunking -> embeddings -> Chroma -> local LLM (Ollama) -> answer with citations. Later: hybrid search and reranking, an evaluation set, and an agent that can query transaction data.

## Status
- [ ] Local LLM and embeddings running
- [ ] Chunking and retrieval
- [ ] Answers with citations

## How to run
To be added.
