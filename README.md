# -Context-Aware-Chatbot-Using-LangChain-and-RAG

This project is a Retrieval-Augmented Generation (RAG) based chatbot that automatically answers user queries.

##  Features

-  Semantic search using FAISS
-  LLM-powered responses (FLAN-T5)
-  Chat-based UI using Streamlit
-  Fast performance with caching
-  Context-aware answers (no hallucination)

##  Tech Stack

- Python
- Streamlit
- LangChain
- FAISS
- HuggingFace Transformers

##  How it Works

1. Support ticket dataset is converted into embeddings
2. FAISS stores vector representations
3. User query → similarity search
4. Retrieved context → LLM generates answer

##  Run Locally

```bash
pip install -r requirements.txt
python build_index.py
streamlit run app.py
