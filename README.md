# AI Faculty Assistant

AI Faculty Assistant is an intelligent chatbot developed to help students quickly access faculty-related information through natural language conversations. The application combines a multi-agent architecture, Retrieval-Augmented Generation (RAG), PostgreSQL, and a local Ollama language model to provide accurate and context-aware responses.

## Features

The assistant can answer questions about professors, courses, exam schedules, faculty regulations, enrollment procedures, student services, and faculty documents. It automatically routes each question to the appropriate agent, allowing efficient retrieval of structured data from a PostgreSQL database as well as semantic search across PDF, DOCX, and TXT documents using FAISS.

## Tech Stack

The backend is built with Python, FastAPI, PostgreSQL, SQLAlchemy, Ollama, FAISS, Sentence Transformers, PyTorch, and Pydantic. The frontend is developed using React, TypeScript, Vite, and Tailwind CSS.

## Running the Project

To start the backend:

```bash
cd ai-faculty-assistant

.venv\Scripts\activate

uvicorn app.main:app --reload
```

To start the frontend:

```bash
npm install

cd C:\Users\JERKOV\Desktop\ai-faculty-assistant\ai-faculty-assistant\frontend

npm run dev
```

## Screenshots

<img width="1146" height="375" alt="image" src="https://github.com/user-attachments/assets/2dfbb9c0-bf47-4cf6-aa1b-894fc3ef3dad" />

<img width="1182" height="902" alt="image" src="https://github.com/user-attachments/assets/11d05ef6-a33c-49b4-b89d-6bf382dd4eaf" />

<img width="1195" height="918" alt="image" src="https://github.com/user-attachments/assets/bd4d1d05-eefa-4330-8c8c-edd3a7478cf5" />

<img width="1150" height="443" alt="image" src="https://github.com/user-attachments/assets/507665fa-cc65-4c53-9117-c5aa7ec54e2a" />

<img width="1198" height="789" alt="image" src="https://github.com/user-attachments/assets/3f64284e-0280-4123-bd34-d99032618e9c" />

## Author

Ivan Jerkov
