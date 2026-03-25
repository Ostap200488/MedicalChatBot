# Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS

A medical chatbot project built with **Python**, **LangChain**, **Pinecone**, **Flask**, and **OpenAI**.  
This application uses LLMs and vector search to provide intelligent medical-related responses.

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/entbappy/Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
cd Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS

2. Create a Conda environment
conda create -n medibot python=3.10 -y
conda activate medibot

3. Install the requirements
pip install -r requirements.txt

4. Create a .env file
Create a .env file in the root directory and add your credentials:
PINECONE_API_KEY="your_pinecone_api_key"
OPENAI_API_KEY="your_openai_api_key"

5. Store embeddings in Pinecone
Run the following command to create and store embeddings in Pinecone:
python store_index.py

6. Start the application
python app.py

7. Open in browser
Once the app is running, open:
http://localhost:5000
