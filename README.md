# documentation-helper
## LangChain Documentation Helper
This is a web application that answers questions about LangChain by referencing the official LangChain documentation. It showcases using LangChain and Pinecone to build a simple generative AI application.

Overview
Allows users to input natural language questions about LangChain
Retrieves relevant passages from LangChain docs to answer the questions


![](https://github.com/quintonmills/documentation-helper/blob/main/banner.gif)



Built using Streamlit for the web interface
Leverages a Pinecone vector database to store docs passages for fast retrieval
Uses LangChain for text embeddings and semantic search to match questions with answers
Running the App
Set up Pinecone
Sign up for a free Pinecone Community account
Create a new vector index
Upload the LangChain documentation passages csv file to populate the index
Update pinecone_config.py with your API keys
Install Requirements
Copy code

