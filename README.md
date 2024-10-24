# 📊 Financial GenAI Chatbot 🤖

Welcome to the **Financial GenAI Chatbot** project! This innovative solution aims to provide seamless answers to company-specific product queries and assist customers in navigating and purchasing products effectively. 

## 🚀 Problem Statement
In today's fast-paced financial landscape, customers need quick and reliable information about products. Our chatbot leverages cutting-edge technology to deliver answers tailored to specific queries, ensuring users can make informed decisions. 

## 🛠️ Project Methodology

1. **Data Collection** 📥  
   We utilized open-source data to gather comprehensive information about company products and their associated Q&A data.

2. **Data Preprocessing** 🔄  
   Using Python, we cleaned and pre-processed the data, saving it into a structured CSV file for easy access.

3. **Vector Database Integration** 🗄️  
   The CSV file was then loaded into a Vector Database using an Embedding Model from Hugging Face, allowing for efficient retrieval of information.

4. **Building the RAG Architecture** 🧩  
   We constructed a Retrieval-Augmented Generation (RAG) QA Chain using Langchain and integrated the Zypher 7B LLM (open source) to enhance the chatbot's capabilities.

5. **Response Evaluation** ✅  
   Finally, we tested the chatbot to ensure it could effectively answer customer queries, refining its performance based on feedback.

## 🌟 Features
- Instant answers to product-related questions
- User-friendly interaction for effective product exploration
- Continuous learning and improvement from user interactions

## 📦 Getting Started
To get started with the Financial GenAI Chatbot:

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/financial-genai-chatbot.git
   ```

2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Load your data and start the chatbot:  
   ```bash
   python chatbot.py
   ```


Thank you for checking out the Financial GenAI Chatbot! We hope it helps you navigate your financial product queries effortlessly. Happy chatting! 💬✨
