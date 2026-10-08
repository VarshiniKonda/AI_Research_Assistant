\# AI Research Assistant



An AI-powered research assistant that uses Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), vector search, and multiple information sources to generate research-based answers.



\## Features



\- Research from article URLs

\- Internet news search

\- Web search

\- Wikipedia research

\- arXiv research

\- Hybrid research using multiple sources

\- RAG-based question answering

\- FAISS vector database

\- Hugging Face embeddings

\- Groq LLM integration

\- Streamlit web interface



\## Technologies Used



\- Python

\- Streamlit

\- LangChain

\- Groq

\- Hugging Face

\- FAISS

\- Sentence Transformers

\- NewsAPI

\- Wikipedia API

\- arXiv

\- DuckDuckGo Search



\## How It Works



1\. User provides one or more research article URLs.

2\. The application extracts the article content.

3\. The content is divided into smaller text chunks.

4\. Hugging Face embeddings are generated.

5\. The embeddings are stored in a FAISS vector index.

6\. The user enters a research question.

7\. Relevant information is retrieved using similarity search.

8\. The retrieved context is passed to the LLM.

9\. The LLM generates the final answer.



\## Project Structure



```text

AI\_Research\_Assistant/

│

├── main.py

├── requirements.txt

├── README.md

├── .gitignore

└── vector\_index.pkl

Installation

Clone the Repository

git clone https://github.com/VarshiniKonda/AI\_Research\_Assistant.git

cd AI\_Research\_Assistant



Create Virtual Environment

python -m venv venv



Activate Virtual Environment

Windows:

venv\\Scripts\\activate



Install Dependencies

pip install -r requirements.txt



API Configuration

The application requires API keys for the configured services.

Add your API keys through the application when prompted.

Never upload API keys, passwords, or .env files to GitHub.

Run the Application

streamlit run main.py



The application will open in your browser through Streamlit.

Example

Input

Article URL:

https://en.wikipedia.org/wiki/Apple\_Inc.



Research Question:

What is Apple and what are its major products?



Output

The application retrieves relevant information from the selected source and generates an AI-powered research answer.

Use Cases

\- Research and information gathering

\- Article analysis

\- Academic research assistance

\- Quick question answering

\- Knowledge retrieval from multiple sources

\- Research using web and academic sources

Learning Outcomes

This project demonstrates practical knowledge of:

\- Large Language Models

\- Retrieval-Augmented Generation

\- Prompt-based question answering

\- Vector embeddings

\- FAISS similarity search

\- LangChain

\- API integration

\- External knowledge retrieval

\- Python development

\- Streamlit application development

Author

Varshini Konda

GitHub: https://github.com/VarshiniKonda

