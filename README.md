

# BhilaiGPT

## Description
BhilaiGPT, a friendly system that helps with all kinds of questions about IIT Bhilai. Using cool tech like Ollama, it gives accurate answers from IIT Bhilai's official documents
RAG (Retrieval-Augmented Generation) in LLM (Large Language Models) refers to a model architecture that combines retrieval-based methods with generation-based methods.

In RAG, a retriever component first selects relevant passages or documents from a large corpus of text based on the input query. Then, a generator component, typically a language model like GPT, processes the retrieved passages to generate a response or output.

This approach aims to improve the quality and relevance of generated responses by leveraging information retrieval techniques to provide context and grounding for the generation process.
This project is divided into two parts: a backend and a frontend. The backend handles the core functionality and the frontend provides the user interface.

## Installation

### Backend
1. Navigate to the `backend` directory: `cd backend`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Download and Install Ollama.
4. Run Ollama: `ollama pull llama2`
5. Change the model name in the **Modelfile.txt** with the name of the model you downloaded.
6. Create a new model: `ollama create BhilaiGPT_1.0 -f "Modelfile.txt"`
7. Run load_data.py for documents storage: `python load_data.py`
8. Run the new model: `ollama run BhilaiGPT_1.0`
9. Start the backend server: `python index.py`

### Frontend
1. Navigate to the `webchat` directory: `cd webchat`
2. Install the required dependencies: `npm install`
3. Start the frontend server: `npm start`
4. Open your browser and go to `localhost:3000`

## Using with Docker
1. Make sure you have docker installed
2. Run `docker buildx build -t bhilai_gpt .` from the root directory to build the image
3. When the image build completed, run `docker run -d -p 5000:5000 -p 3000:3000 --name BhilaiGPT bhilai_gpt` to start the container
4. Open your browser and go to `localhost:3000`

## Usage
Once both the backend and frontend servers are running, you can interact with the application by opening it in your web browser. Follow the on-screen instructions to utilize the features provided.

## Contributors
- [Rohar Kumar Mishra]



