# 🚀 LinkedIn Post Generator using LLM + APIs

This is a Generative AI-powered tool to **automate the creation of engaging LinkedIn posts** using **LLaMA 3.2**, **LangChain**, **Groq API**, and a **Streamlit interface**. It helps users craft impactful content with just a few clicks — tailored by tone, language, and length.

![Demo](https://img.youtube.com/vi/qZ_J-Xg0QM4/0.jpg)

🔗 [Watch Demo on YouTube](https://www.youtube.com/watch?v=qZ_J-Xg0QM4)

---

## ✨ Features

- 🧠 **Powered by LLaMA 3.2 via Groq API** — Fast, intelligent text generation
- 🔗 **LangChain integration** — Structured and modular prompt chaining
- 🎯 **Customizable tone, language, and length** — Write like YOU
- 🌐 **English & Hinglish support**
- ⚡ **Streamlit UI** — Real-time post creation in under 500ms

---

## 🛠️ Tech Stack

- **LLM**: LLaMA 3.2 (via Groq API)
- **Prompt Framework**: LangChain
- **Frontend**: Streamlit
- **Languages Supported**: English, Hinglish
- **Others**: Python 3.10+, dotenv

---

## 🛠️ Tech Stack

- **LLM**: LLaMA 3.2
- **Inference**: Groq API
- **Framework**: LangChain
- **UI**: Streamlit
- **Language Support**: English & Hinglish

## 🧠 How It Works

1. User selects tone, length, and inputs a topic.
2. Generator builds a few-shot prompt with user style and context.
3. LLaMA 3.2 via Groq API crafts a polished LinkedIn post.
4. Streamlit UI displays the result for easy copy or export.

## 🚀 Getting Started

```bash
git clone https://github.com/…/LinkedIn-Post-Generator
cd LinkedIn-Post-Generator
pip install -r requirements.txt
streamlit run app.py

export GROQ_API_KEY=your_api_key
export OPENAI_API_KEY=your_openai_key  # if used for embeddings/templates
