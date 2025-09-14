# 📰 News Summarizer & Q\&A — Gemini vs Hugging Face

This is a Streamlit web app that compares **Gemini** and **Hugging Face BART models** for news summarization and allows you to **ask questions** about the article.

---

## 🚀 Features

* Loads a news article from any URL.
* View the **original word count**.
* Generates **two model-based summaries**:

  * **Gemini** summary (Google Gemini API)
  * **Hugging Face BART** summary
* Lets you **ask a custom question** related to the article.
* Compare **response times** between both models.

---

## How to Run Locally

1️⃣ **Clone the repository**

```bash
git clone <repo-url>
cd <repo-folder>
```

2️⃣ **Set up a virtual environment** (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

3️⃣ **Install the required packages**

```bash
pip install -r requirements.txt
```

4️⃣ **Add your API credentials**
Create a file `.streamlit/secrets.toml` and add:

```toml
GEMINI_API_KEY = "your_gemini_key"
HF_TOKEN = "your_huggingface_key"
```

5️⃣ **Run the application**

```bash
streamlit run app.py
```

The app will open in your browser (default: `http://localhost:8501`).

---

## 📦 Technology Stack

* **Python**, **Streamlit**
* **Google Gemini API**
* **Hugging Face Transformers (BART)**

---

