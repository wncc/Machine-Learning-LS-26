# Week 3 Assignment — RAG-Powered Console Chatbot

Welcome to Week 3's assignment. This week you build something real: a chatbot that can answer questions about ML concepts by retrieving relevant information from a document corpus — rather than hallucinating answers from memory.

**Format:** Fill-in-the-blank notebook. Setup, models, and corpus are provided. You implement each stage of the pipeline. Every `[TODO]` is followed by a Sanity Check.

**How to start:**
1. Click the Colab link below
2. Go to `File` → `Save a copy in Drive`
3. Paste your HuggingFace token in the setup cell
4. Work top to bottom — do not skip a failing Sanity Check

---

## The Main Mission: RAG Chatbot (Mandatory — Parts A + B)

**Part A — Concept Check:** Four written questions on Transformer architecture, encoder vs decoder, RLHF, and RAG. 2–4 sentences each.

**Part B — Core Implementation:** Build the full RAG pipeline:
- `embed_text()` — embed a string into a dense vector
- `chunk_documents()` — split documents into overlapping chunks
- `build_index()` — embed all chunks and store in FAISS
- `retrieve()` — find the top-k most relevant chunks for a question
- `build_prompt()` — format retrieved chunks into an LLM-ready prompt
- `generate_answer()` — call the LLM and extract the response
- `rag_answer()` — wire all of the above into one function
- `run_chatbot()` — the interactive console loop

📎 [Open in Colab — Console Chatbot Assignment](https://colab.research.google.com/drive/1tL4OaEcv5_lIllmxW7wzB0RENME558I_?usp=sharing)

---

## The Challenge (Optional — Part C)

Choose one:

**Option 1 — Multi-Turn Memory:** Make the chatbot remember previous turns so it can handle follow-up questions like "What was it trained on?" after asking "What is BERT?"

**Option 2 — Source Citation:** After each answer, display the retrieved source chunks and their similarity scores so the user knows where the answer came from. Bonus: tag each chunk with its source document ID.

---

## Evaluation

| Section | Weight | What we look at |
|---|---|---|
| Part A (Concept Check) | 25% | Accuracy, depth, your own words — not copy-paste from the README |
| Part B (Implementation) | 50% | All Sanity Checks pass, clean readable code |
| Part C (Challenge) | 15% | Correctness and approach |
| Reflection | 10% | Genuine engagement with what worked and what didn't |

---

## Submission

Share your completed Colab notebook (File → Share → Anyone with the link → Viewer) and submit the link to the WnCC submission form by the end of Week 3.
