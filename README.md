This Python script implements a question-answering system specifically designed to answer questions related to the Harry Potter book series. It utilizes advanced natural language processing (NLP) techniques and models from Hugging Face, combined with LangChain for document retrieval and processing.

**Features**

Multiple Models: The system supports multiple language models trained on large datasets, including wizardLM, llama2-7b-chat, llama2-13b-chat, and mistral-7B.
Text Splitting and Embeddings: The script splits the text into chunks and creates embeddings for efficient processing and retrieval.
Question Answering Pipeline: Utilizes Hugging Face pipelines for generating answers to user queries.
Retriever Chain: Implements a retriever chain for retrieving relevant passages from the Harry Potter books.
Post-processing: Formats and presents the answers along with the sources used.

**Usage**

Environment Setup: Ensure you have the required Python environment set up with the necessary dependencies installed.
Model Selection: Choose the desired language model from the available options (wizardLM, llama2-7b-chat, llama2-13b-chat, or mistral-7B).
Run the Script: Execute the Python script, providing your questions as input.
Get Answers: The system will generate answers based on the provided questions, citing relevant passages from the Harry Potter books.

**Example Queries**

"Which challenges does Harry face during the Triwizard Tournament?"
"Is Malfoy an ally of Voldemort?"
"What are Horcruxes?"
"Give me 5 examples of cool potions and explain what they do."

**Dependencies**
LangChain: A library for natural language processing tasks.
Hugging Face Transformers: Provides pre-trained models and tools for NLP tasks.
FAISS: A library for efficient similarity search and clustering of dense vectors.

**Credits**
This script was developed as part of a project to explore question answering systems and NLP techniques.
Inspired by the Harry Potter book series by J.K. Rowling.
