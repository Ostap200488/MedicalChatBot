# Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-

A medical chatbot project built with **Python**, **LangChain**, **Pinecone**, **Flask**, and **OpenAI**.  
This application uses LLMs and vector search to provide intelligent medical-related responses.

## How to Run

1. Create a Conda environment
conda create -n medibot python=3.10 -y
conda activate medibot

2. Install the requirements
pip install -r requirements.txt

3. Create a .env file
Create a .env file in the root directory and add your credentials:
PINECONE_API_KEY="your_pinecone_api_key"
OPENAI_API_KEY="your_openai_api_key"

4. Store embeddings in Pinecone
Run the following command to create and store embeddings in Pinecone:
python store_index.py

5. Start the application
python app.py

6. Open in browser
Once the app is running, open:
http://localhost:5000
