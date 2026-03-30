An AI-powered medical chatbot application built using modern LLM technologies.
This project demonstrates how large language models can be integrated into real-world applications to provide intelligent, context-aware responses based on medical data.
It combines LangChain, vector embeddings, and a Flask backend to simulate a real healthcare assistant experience.
 GitHub Repository:
https://github.com/entbappy/Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
 # Key Features
 AI-powered question answering using LLMs
 Context-aware responses using vector embeddings
 Semantic search with Pinecone
 Backend API built with Flask
 Clean modular structure for scalability
 Environment-based configuration for security
# Tech Stack

Python
LangChain
Flask
OpenAI API (GPT models)
Pinecone (Vector Database)
# How It Works
Documents are processed and converted into embeddings
Embeddings are stored in Pinecone
User queries are matched against relevant context
The LLM generates accurate, contextual responses
This approach allows the chatbot to provide more reliable and domain-specific answers instead of generic responses.
# Getting Started
1. Clone the Repository
git clone https://github.com/entbappy/Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
cd Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS
2. Create and Activate Conda Environment
conda create -n medibot python=3.10 -y
conda activate medibot
3. Install Dependencies
pip install -r requirements.txt
4. Setup Environment Variables
Create a .env file in the root directory:
PINECONE_API_KEY=your_pinecone_api_key
OPENAI_API_KEY=your_openai_api_key
5. Create Embeddings Index
python store_index.py
6. Run the Application
python app.py
7. Open in Browser
http://localhost:8080
# Project Structure (Simplified)
├── app.py              # Flask application entry point  
├── store_index.py      # Embedding & Pinecone indexing  
├── src/                # Core logic (helpers, chains, etc.)  
├── templates/          # Frontend UI (HTML)  
├── static/             # Static assets  
├── requirements.txt    # Dependencies  
├── .env                # API keys (not committed)  
 What I Learned
Building AI-powered applications using LangChain
Working with vector databases (Pinecone) for semantic search
Integrating LLMs into backend systems
Managing environment variables securely
Debugging real-world dependency issues (LangChain updates, API configs)
# Future Improvements
Add authentication (user sessions)
Improve UI/UX for better user experience
Add streaming responses for real-time interaction
Deploy using cloud services (AWS / Docker)
Expand dataset for better medical coverage
 Disclaimer
This project is for educational purposes only and should not be used as a substitute for professional medical advice.
# About Me
Hi! I'm Orest Demchuk, a Junior Software Developer passionate about building real-world applications and integrating AI into practical solutions.
💻 Full-stack development (React, Node.js, MongoDB)
🤖 AI integrations (OpenAI, LangChain, Pinecone)
☁️ Currently learning cloud & scalable systems
⭐ Final Note
This project highlights my ability to combine AI, backend development, and real-world problem solving into a functional application.
I’m actively improving it and exploring ways to deploy and scale it in production environments.
