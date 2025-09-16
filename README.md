# chatbot

### Chatbot using Python Full Stack 🦙💬
This project is an interactive LLaMA 2 chatbot built with Streamlit, powered by Replicate API.
It demonstrates how to integrate LLM models into a full-stack Python application with an intuitive UI, customizable parameters, and chat history management.

### 🚀 Features
. 🔑 Secure API Key Handling – Supports st.secrets or manual entry.
. 🦙 LLaMA 2 Models – Choose between 7B and 13B versions.
. ⚙️ Customizable Parameters – Adjust temperature, top_p, and max_length.
. 💬 Chat Interface – Interactive chat messages using Streamlit's st.chat_message.
. 🧹 Clear History – Reset conversations with one click.
. ⚡ Streaming Responses – See model output generate in real time.

### 🛠️ Tech Stack
. Python 🐍
. Streamlit – Frontend & Chat UI
. Replicate API – LLaMA 2 inference
. os & environment variables – Credential management

### 📦 Installation
1. Clone the repository:
-  git clone https://github.com/saiharshith123/chatbot-using-python-full-stack.git
-  cd chatbot-using-python-full-stack

2. Create a virtual environment & activate it:
- python -m venv venv
- source venv/bin/activate   # Mac/Linux
- venv\Scripts\activate      # Windows

3. Install dependencies:
- pip install -r requirements.txt

4. Add your Replicate API Token:
Option 1: Store in Streamlit secrets (.streamlit/secrets.toml)
- REPLICATE_API_TOKEN = "your_api_key_here"
Option 2: Enter directly in the app sidebar.

### ▶️ Usage
. Run the Streamlit app:
- streamlit run app.py
. Then open the link in your browser (usually http://localhost:8501).

### ⚙️ Project Structure
chatbot-using-python-full-stack/
│── app.py               # Main Streamlit application
│── requirements.txt     # Dependencies
│── README.md            # Project documentation
│── .streamlit/          # Secrets/configuration (optional)

### 📚 Resources
. Streamlit Docs
. Replicate API
. How to Build a LLaMA 2 Chatbot

### 🤝 Contributing
Contributions are welcome! Please fork this repo and submit a PR with improvements.

### 📜 License
This project is licensed under the MIT License.
