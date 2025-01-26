# Medical-ChatBot-GenAI
Medical ChatBot GenAI is a web-based chatbot application that utilizes the power of OpenAI's GPT and Pinecone vector databases for advanced question-answering capabilities. It is designed to answer medical-related queries based on embedded document chunks. The chatbot leverages the langchain library to combine various AI components, making it a robust and scalable solution for the healthcare industry.
# Features
Natural language processing (NLP) powered by OpenAI's GPT.
Retrieval-Augmented Generation (RAG) for more accurate and context-aware answers.
Integration with Pinecone to manage and search document embeddings efficiently.
Easy-to-use Flask web interface for seamless interaction.
# Technologies Used
Flask: A lightweight web framework for serving the chatbot interface.
OpenAI GPT: Used for generating responses to user queries.
Pinecone: A vector database for storing and searching document embeddings.
Langchain: A framework to integrate different AI components, enabling the RAG model.
Hugging Face Embeddings: Used to generate embeddings for documents.
Python-dotenv: To securely load environment variables for API keys.
# Usage 
Visit the web interface at http://127.0.0.1:8080 after running the app.
Enter a medical-related question into the chatbot, and it will provide a response based on the embedded document database.
