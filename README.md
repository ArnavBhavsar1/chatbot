# 🤖 LLM Chatbot (Streamlit + OpenAI)

An interactive AI chatbot built using **Streamlit** and **OpenAI API**.
This chatbot can understand user queries and respond intelligently in real-time with conversational memory.

---

## 🚀 Features

* 💬 ChatGPT-like interface using Streamlit
* 🧠 Conversational memory (remembers chat history)
* ⚡ Fast responses using OpenAI (`gpt-4o-mini`)
* 🔐 Secure API key handling with `.env`
* 🎯 Beginner-friendly and easy to extend

---

## 🛠 Tech Stack

* **Python**
* **Streamlit**
* **OpenAI API**
* **python-dotenv**

---

## 📁 Project Structure

```
llm_chatbot/
│── app.py              # Main chatbot application
│── requirements.txt   # Dependencies
│── .env               # API key (not shared)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/llm-chatbot.git
cd llm-chatbot
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Add OpenAI API Key

Create a `.env` file in the root folder:

```
OPENAI_API_KEY=your_api_key_here
```

---

### 4️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 💡 How It Works

1. User enters a query in the chat input
2. The query is sent to OpenAI API
3. The model processes the request
4. Response is displayed in real-time
5. Chat history is stored for context

---

## 📌 Resume Highlight

> Built an AI chatbot using OpenAI API and Streamlit with conversational memory and real-time response handling.

---



