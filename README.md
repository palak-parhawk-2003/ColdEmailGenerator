# 📧 ColdEmailGenerator

ColdEmailGenerator is an intelligent Streamlit application that automatically generates cold emails for business outreach based on job listings found on company career pages. It leverages the power of LLMs (like LLaMA 3) via Groq API and custom portfolio matching using ChromaDB.

---

## 🚀 Features

- 🔗 Scrape and parse job descriptions from company career pages
- 🤖 Use LLMs to extract job roles, experience, skills, and descriptions
- ✉️ Automatically generate tailored cold emails using LangChain and Groq
- 📌 Recommends the most relevant portfolio links using ChromaDB
- ⚡ Fast and interactive UI built with Streamlit

---

## 🛠️ Tech Stack

- **Python**
- **LangChain + Groq**
- **ChromaDB**
- **Streamlit**
- **Pandas**
- **Dotenv**

---

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside app/.env update the value of GROQ_API_KEY with the API_KEY you created.

2. To get started, first install the dependencies using: pip install -r requirements.txt

3. Run the streamlit app: streamlit run app/main.py
