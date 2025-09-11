# Medical-RAG-Chatbot
This implementation loads domain‑specific PDFs, splits them into manageable chunks, and selects the most relevant sections via keyword/manual matching instead of embeddings. It then builds a context‑grounded prompt for a medical RAG chatbot, runs it through GPT‑4o‑mini with guardrails, and returns only safe, faithful answers.
