# EmpathyBot 🤖❤️

[cite_start]EmpathyBot is a functional prototype of a chatbot that analyzes a user's emotions from text inputs and responds with kind, contextually appropriate replies[cite: 19]. [cite_start]This project was developed in a 6-hour sprint to showcase the power of AI-driven emotional intelligence for applications like mental health support or enhanced customer service[cite: 8, 9].

The core of EmpathyBot is its use of advanced Retrieval-Augmented Generation (RAG) combined with few-shot prompt engineering. [cite_start]This allows it to select and frame empathetic responses from a large corpus without requiring heavy model training[cite: 20, 34].

## 🚀 Key Features

* [cite_start]**Emotion Detection**: Utilizes a pre-trained transformer model to accurately identify user emotions like happiness, sadness, and anger from text inputs[cite: 38].
* [cite_start]**Advanced RAG System**: Employs Sentence-Transformers and FAISS to efficiently retrieve the most relevant empathetic response templates from a large corpus based on the detected emotion[cite: 46, 48, 97, 98].
* [cite_start]**Few-Shot Prompting**: Dynamically frames responses to feel natural and human-like[cite: 34].
* [cite_start]**Web Interface**: A simple and intuitive web-based chat interface built with Streamlit[cite: 25, 50].
* [cite_start]**Safety First**: All responses are designed to be safe and positive, and every reply includes a disclaimer to seek professional help for serious issues[cite: 12].

## 🛠️ Tech Stack

* [cite_start]**Platform**: Google Colab [cite: 43]
* **Core Libraries**:
    * [cite_start]Hugging Face `transformers` for emotion detection models[cite: 45].
    * [cite_start]`sentence-transformers` for creating text embeddings[cite: 46].
    * [cite_start]`faiss-cpu` for efficient similarity search[cite: 48, 81].
    * [cite_start]`pandas` and `nltk` for data handling and preprocessing[cite: 52].
* **Frontend/Deployment**:
    * [cite_start]`Streamlit` for the web interface[cite: 50].
    * [cite_start]`FastAPI` and `uvicorn` as an alternative API endpoint option[cite: 51].
* [cite_start]**Version Control**: Git [cite: 53]

## ⚙️ Setup and Installation

Follow these steps to get your local instance of EmpathyBot running.
