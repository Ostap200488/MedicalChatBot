# Step 1: Create and Activate a Virtual Environment
After cloning the repository, create a Conda environment:
conda create -n medibot python=3.10 -y
conda activate medibot
# Step 2: Install Dependencies
Install all required packages using:
pip install -r requirements.txt
# Step 3: Configure Environment Variables
Create a .env file in the root directory and add your API keys:
PINECONE_API_KEY=your_pinecone_api_key
OPENAI_API_KEY=your_openai_api_key
# Step 4: Initialize Embeddings
Run the following command to store embeddings in Pinecone:
python store_index.py
# Step  5: Start the Application

# Launch the app with:
python app.py
# Step 6: Open the App
Go to your browser and visit:
http://localhost:5000
(Port may vary depending on your Flask configuration)
