# LinkedIn Post Generator Tool 🚀

A Gen‑AI tool that automates the creation of LinkedIn posts using LLaMA 3.2, LangChain, and Streamlit, enabling users to generate on‑brand, professional content instantly.

## 🔧 Features

- Powered by **LLaMA 3.2** (via Groq API) for fast, intelligent text generation :contentReference[oaicite:2]{index=2}  
- Crafted with **LangChain** for structured prompt chaining and context management :contentReference[oaicite:3]{index=3}  
- **Custom tone & style** adaptation using few-shot prompting to match user voice :contentReference[oaicite:4]{index=4}  
- User‑friendly **Streamlit UI** for effortless interaction :contentReference[oaicite:5]{index=5}  
- Supports multiple **post lengths** (short/medium/long) and languages (English, Hinglish) :contentReference[oaicite:6]{index=6}

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
