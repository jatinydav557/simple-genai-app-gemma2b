
---

````markdown
# 🧠 LangChain ✨ Streamlit Chatbot with Ollama Gemma (2B)

This project is a **minimal LLM chatbot interface** built with [LangChain](https://www.langchain.com/), [Streamlit](https://streamlit.io/), and [Ollama](https://ollama.com/).  
It demonstrates prompt templating, LangSmith tracing, and integrates the lightweight `gemma:2b` model locally using Ollama.

---

## 📺 Demo

▶️ **YouTube Walkthrough**: [Watch Here](https://www.youtube.com/watch?v=dQw4w9WgXcQ)  
<!-- Replace this link with your real YouTube video -->

---

## 🧩 Key Features

- ⚙️ **LangChain + Ollama** integration
- 🤖 Uses local `gemma:2b` LLM via `Ollama`
- 🧠 Prompt Engineering with `ChatPromptTemplate`
- 📊 LangSmith Tracing for real-time chain visualization
- 💻 Frontend: Streamlit-powered chat interface

---

## 📁 Project Structure

```plaintext
.
├── app.py              # Main Streamlit app
├── .env                # Environment variables for LangChain
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
````

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/yourusername/ollama-sample-genai-app.git
cd ollama-sample-genai-app
```

### 2️⃣ Install Dependencies

Using `uv` or `pip`:

```bash
uv pip install -r requirements.txt
# OR
pip install -r requirements.txt
```

### 3️⃣ Setup `.env`

Create a `.env` file in the root directory:

```env
LANGCHAIN_API_KEY= Get the key from langchain's official website
LANGCHAIN_PROJECT= Whatever you want to name the project
```

### 4️⃣ Run Ollama Model

Ensure Ollama is installed and running:

```bash
ollama run gemma:2b
```

### 5️⃣ Launch the App

```bash
streamlit run app.py
```

---

## 📦 Dependencies

Listed in `requirements.txt`:

```
langchain
langchain_community
langchain-openai
python-dotenv
ipykernel
beautifulsoup4
faiss-cpu
streamlit
```

---

## 🙋‍♂️ About Me

I’m a passionate Data Science & GenAI developer building end-to-end AI applications using **LangChain**, **MLOps**, and **LLMs**.

📌 Looking for roles in:
🧠 AI / LLM Engineering • 📊 Data Science • ⚙️ MLOps • 🧩 GenAI R\&D

🔗 [LinkedIn](https://www.linkedin.com/in/yourname)
🌐 [Portfolio Website](https://yourwebsite.com)

---

## 🏁 What's Next?

* Add Memory, Tool usage, or Vector DB (e.g., FAISS)
* Convert to FastAPI + LangServe backend
* Deploy to GCP / Hugging Face Spaces / Streamlit Cloud

---

⭐ If you like this project, give it a **star** and fork it to build your own!

```

---

✅ Now just **replace these placeholders**:

- `https://www.youtube.com/watch?v=dQw4w9WgXcQ` → Your actual YouTube demo link  
- `yourusername` → Your GitHub username  
- `https://www.linkedin.com/in/yourname` → Your LinkedIn profile  
- `https://yourwebsite.com` → Your portfolio website (optional)

Let me know if you'd like help uploading to GitHub or generating a thumbnail too.
```
