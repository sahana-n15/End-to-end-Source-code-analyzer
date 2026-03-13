# Medical Assistant

A conversational AI medical chatbot built with Flask, LangChain, Pinecone, and OpenAI. Ask any medical question and get accurate answers based on a medical knowledge base.

-----

## 📸 Screenshots

<img width="1821" height="942" alt="image" src="https://github.com/user-attachments/assets/633511e8-de98-47fb-b5d7-1e89f3e86488" />


-----

## 🚀 Features

- 💬 Real-time chat interface
- 🧠 AI-powered answers using OpenAI LLM
- 📚 Medical knowledge base using Pinecone Vector Store
- 🔍 Retrieval Augmented Generation (RAG) pipeline
- 🎨 Clean and responsive UI

-----

## 🛠️ Tech Stack

|Technology            |Purpose              |
|----------------------|---------------------|
|Python + Flask        |Backend web framework|
|LangChain             |LLM orchestration    |
|OpenAI                |Language model       |
|Pinecone              |Vector database      |
|HuggingFace Embeddings|Text embeddings      |
|HTML + CSS + jQuery   |Frontend UI          |
|Bootstrap 4           |UI styling           |

-----

## 📁 Project Structure

```
Medical-Chatbot/
│
├── app.py                  # Flask app and routes
├── store_index.py          # Load PDFs and store in Pinecone
├── setup.py                # Package setup
├── template.py             # Template utility
├── test.py                 # Testing file
├── templates/
│   └── chat.html           # Chat UI
├── static/
│   └── style.css           # Custom styles
├── src/
│   ├── _init_.py
│   ├── helper.py           # Helper functions
│   └── prompt.py           # Prompt templates
├── research/
│   └── trials.ipynb        # Research notebooks
├── Data/
│   └── medical_book.pdf    # Medical knowledge base
├── .env                    # API keys (not committed)
├── .gitignore
├── requirements.txt        # Python dependencies
├── LICENSE
└── README.md
```

-----

## ⚙️ Setup & Installation

*1. Clone the repository:*

bash
git clone https://github.com/sahana-n15/Medical-Chatbot.git
cd Medical-Chatbot


*2. Create and activate conda environment:*

bash
conda create -n llmapp python=3.10
conda activate llmapp


*3. Install dependencies:*

bash
pip install -r requirements.txt


*4. Create a .env file and add your API keys:*


OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
PINECONE_ENV=your_pinecone_environment


*5. Add your medical PDF to the Data/ folder*

*6. Run store_index.py to load data into Pinecone:*

bash
python store_index.py


*7. Run the app:*

bash
python app.py


*8. Open your browser and go to:*


http://localhost:8080


-----

## 🔑 Environment Variables

|Variable          |Description              |
|------------------|-------------------------|
|OPENAI_API_KEY  |Your OpenAI API key      |
|PINECONE_API_KEY|Your Pinecone API key    |
|PINECONE_ENV    |Your Pinecone environment|

-----

## 👩‍💻 Author

*Sahana*

- GitHub: [@sahana-n15](https://github.com/sahana-n15)

-----

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
