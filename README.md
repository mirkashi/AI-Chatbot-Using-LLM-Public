# LangChain + Streamlit Chatbot  
### A Beautiful Conversational AI Chatbot with Memory

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![LangChain](https://img.shields.io/badge/LangChain-Latest-green)
![OpenAI](https://img.shields.io/badge/OpenAI-gpt--4o--mini-000000.svg?style=flat&logo=openai)
![Streamlit](https://img.shields.io/badge/Streamlit-1.30%2B-red)

Ek simple lekin powerful chatbot jo **gpt-4o-mini** use karta hai aur poori baat-cheet yaad rakhta hai (chat history with memory).

Live Demo (after deploy): Coming Soon  
Made with love by **Mariyam Siddiqui**

---

## Features
- Real-time conversation with OpenAI
- Full chat history (session mein sab yaad rehta hai)
- Clean & responsive Streamlit UI
- Toggle to show/hide chat history
- Easy to customize model & temperature

---

## Screenshot
![Chatbot Screenshot](https://via.placeholder.com/800x500.png?text=Chatbot+Screenshot+Here)  
*(Deploy karne ke baad yahan real screenshot daal dena)*

---

## Quick Start (Copy-Paste & Run)

```bash
# 1. Project download karo
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# 2. Virtual environment banao (recommended)
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Mac/Linux

# 3. Dependencies install karo
pip install -r requirements.txt

# 4. Apna OpenAI key daalo (.env file banao)
echo OPENAI_API_KEY=sk-... >> .env

# 5. App chalao!
streamlit run app.py

├── app.py                  Main Streamlit + LangChain code
├── .env                    Your OpenAI key (git ignore mein hai)
├── requirements.txt        All dependencies
└── README.md               Yeh file

# app.py mein sirf yeh 3 lines change karo:

model_name = "gpt-4o-mini"     → "gpt-4o" ya "gpt-3.5-turbo" kar sakte ho
temperature = 0.7              → 0.3 (serious) ya 1.0 (creative)


### Ab yeh 2 files bhi bana lo (optional lekin highly recommended)

#### `requirements.txt`
```txt
streamlit
langchain
langchain-community
langchain-openai
python-dotenv
.env
venv/
__pycache__/
*.pyc
