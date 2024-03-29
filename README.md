

# BhilaiGPT

## Description
BhilaiGPT, a friendly system that helps with all kinds of questions about IIT Bhilai. Using cool tech like Ollama, it gives accurate answers from IIT Bhilai's official documents
RAG (Retrieval-Augmented Generation) in LLM (Large Language Models) refers to a model architecture that combines retrieval-based methods with generation-based methods.

In RAG, a retriever component first selects relevant passages or documents from a large corpus of text based on the input query. Then, a generator component, typically a language model like GPT, processes the retrieved passages to generate a response or output.

This approach aims to improve the quality and relevance of generated responses by leveraging information retrieval techniques to provide context and grounding for the generation process.
This project is divided into two parts: a backend and a frontend. The backend handles the core functionality and the frontend provides the user interface.

## Installation

### Backend
1. Navigate to the `back-end` directory: `cd backend`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Download and Install Ollama.
4. Run Ollama: `ollama run llama2`
5. Create a new model: `ollama create BhilaiGPT_3.95 -f "Modelfile.txt"`
6. Run the new model: `ollama run new BhilaiGPT_3.95`
7. Start the backend server: `python index.py`

### Frontend
1. Navigate to the `webchat` directory: `cd webchat`
2. Install the required dependencies: `npm install`
3. Start the frontend server: `npm start`
4. Open your browser and go to `localhost:3000`

## Usage
Once both the backend and frontend servers are running, you can interact with the application by opening it in your web browser. Follow the on-screen instructions to utilize the features provided.

## Contributors
- [Rohar Kumar Mishra]



