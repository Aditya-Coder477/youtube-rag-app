# YouTube RAG Streamlit App

## Project Description
This project is a **YouTube RAG (Retrieval-Augmented Generation) application** built with **Streamlit** and **LangChain**.  
It allows users to:

- Fetch transcripts from YouTube videos using the **YouTube Transcript API**.
- Split the transcript into chunks and create embeddings using **HuggingFace models**.
- Store embeddings in a **vector store (FAISS)** for semantic search.
- Generate responses or insights based on user queries using embeddings and **Google Generative AI**.
- Use **text-to-speech (gTTS)** for audio output (optional).

The project leverages modern NLP techniques and retrieval-based pipelines to provide accurate and context-aware answers from YouTube content.

---

## Folder Structure
youtube-rag-app/
│
├─ app.py # Main Streamlit app
├─ supporting_functions.py # Helper functions for embeddings & vector store
├─ requirements.txt # All dependencies
├─ README.md # Project documentation

## Installation (Local Setup)
1. **Clone the repository**
git clone https://github.com/<your-username>/youtube-rag-app.git
cd youtube-rag-app

2.Create and activate a virtual environment
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

3.Install dependencies
pip install -r requirements.txt

4.Run the Streamlit app
streamlit run app.py



