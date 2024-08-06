# Intelligent-Document-Query-System-Project
Overview
An end-to-end document Q&A application using AWS Bedrock and LangChain. This project converts PDFs into vector embeddings for efficient querying with models like Cloudy and Llama 2. It includes data injection, vector storage, and a Streamlit app for user interaction.

Features
Efficient Querying: Uses AWS Bedrock and LangChain to transform PDFs into vector embeddings.
Interactive UI: Streamlit-based interface for seamless document querying and response generation.
Advanced Embeddings: Incorporates Amazon Titan and OpenAI embeddings for flexible data processing.
Robust Data Management: Implements a vector store for quick similarity searches and improved system performance.
Technologies Used
Languages: Python, SQL, R
Tools: Git, GitHub, VS Code, PyCharm, Jupyter Notebook, Google Collab
Frameworks: AWS Bedrock, LangChain, Streamlit, PyPDF, Amazon Titan, Llama 2
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/intelligent-document-query-system.git
cd intelligent-document-query-system
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Configure AWS Services:

Ensure you have the necessary AWS credentials configured for accessing AWS Bedrock and other services.
Load PDF Documents:

Place your PDF documents in the data/pdfs directory or specify your own folder.
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Usage
Upload PDFs:

Open your browser and go to http://localhost:8501.
Upload PDF documents through the Streamlit interface.
Start Querying:

Use the provided interface to enter your queries and receive responses.
