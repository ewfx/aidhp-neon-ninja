# 🚀 AI-Powered Hyper-Personalization Engine

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo] Uploaded in artifacts folder with requirement.docx file
- [Inspiration] The purpose and inspiration behind this hackathon are to leverage cutting-edge AI to deliver uniquely tailored experiences, significantly boosting customer       satisfaction and deepening engagement. Inspired by the vision to empower individuals, we're dedicated to providing personalized financial solutions that align seamlessly     with each customer's specific goals, preferences, and lifestyle, driving meaningful connections and financial well-being.
- [What It Does] It can intelligently analyze complex customer data and generate dynamic, personalized recommendations and insights at scale
- [How We Built It] We built is using gen ai models and hugging face transformers. To display data we used streamlit
- [Challenges We Faced](#challenges-we-faced)
- [How to Run] streamlit run  Hyperpersonal_neonninja.py
- [Tech Stack]
  Streamlit
  LLaMA-3.3-70B via Groq API
  Hugging Face Transformers
  SentenceTransformer + Cosine Similarity
  Whisper
  EasyOCR + BLIP, Plotly
- [Team] NeonNinja

---

## 🎯 Introduction
Generative AI-powered Hyper-Personalization Engine that leverages customer data and multimodal inputs (text, voice, image) to provide tailored financial insights and recommendations

## 🎥 Demo
📹 [Video Demo](#) Uploaded to artifacts folder 
🖼️ Screenshots:

![Screenshot 1](link-to-image)

## 💡 Inspiration
The purpose and inspiration behind this hackathon are to leverage cutting-edge AI to deliver uniquely tailored experiences, significantly boosting customer satisfaction and deepening engagement. Inspired by the vision to empower individuals, we're dedicated to providing personalized financial solutions that align seamlessly with each customer's specific goals, preferences, and lifestyle, driving meaningful connections and financial well-being.

## ⚙️ What It Does
It provides 5 features to the customer that gives 360 degree view in accordance to their transaction history and sentiments.

## 🛠️ How We Built It
We built is using gen ai models and hugging face transformers. To display data we used streamlit

## 🚧 Challenges We Faced
To get a constant and relevant response from the model
To incldue all type of input format and provide that to model 

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/ewfx/aidhp-neon-ninja
   ```
2. Install dependencies  
   ```sh
    pip install streamlit pandas python-dotenv llama-index llama-index-llms-groq sentence-transformers numpy transformers torch scikit-learn openai-whisper audio-recorder-       streamlit Pillow plotly openpyxl easyocr

   ```
3. Run the project  
   ```sh
   streamlit run  Hyperpersonal_neonninja.py
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: Streamlit
- 🔹 LLM: LLaMA-3.3-70B via Groq API
- 🔹 Sentiment Analysis	: PostgreSQL / Firebase
- 🔹 Vector Similarity	: MiniLM + Cosine similarity
- 🔹 Voice Transcription	: Whisper


## 👥 Team
- **Puspanjali Dash** - puspanjali7 | [LinkedIn](#)
- **Mragya Rao** - mragya5 | [LinkedIn](#)
