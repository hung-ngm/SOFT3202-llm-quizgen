# SOFT3202 LLM QuizMe

My attempt to create a quiz generator to help me with my exam revision, using LLM such as OpenAI GPT-3.5

## Tech Stack:
- Langchain
- OpenAI API
- Streamlit

## How to run:

### Ingest document:
- Run this step to embed the documents and store with local Chromadb using GPT-3.5 and ChromaDB:
  
`python ingest.py`

### Run the app locally
- Run the Streamlit App locally

`streamlit run streamlit_app.py`

- Enter your OpenAI API Key and start using the app

## Notes:
- You can experiment with the starting prompt with `generate_quizzes()` function inside `streamlit_app.py`