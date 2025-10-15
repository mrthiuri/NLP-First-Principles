# 🧠 Understanding Language: NLP from First Principles

> *“How do machines learn to understand language?”*  
> This project started as me trying to answer that question — not with a fancy library, but from scratch.  
> I’d just discovered large language models and wanted to trace NLP back to its roots: from tokenization and Bag-of-Words to embeddings and real-world applications.

---

## 🌍 What This Is
A hands-on journey through **Natural Language Processing** — from rule-based systems to statistical and neural approaches.  
It’s part tutorial, part playground, part *“hey-I-was-curious-so-I-built-this.”*

If you’ve ever looked at an LLM and thought *“okay, but how did we get here?”* — this notebook is for you.

---

## 📘 Main Notebook — *Understanding Language.ipynb*

The core notebook walks through NLP step-by-step, building concepts and mini-models from scratch.

### Topics covered
- 🧩 Why language is hard for machines  
- 🕰️ From early rule-based NLP to statistical models  
- ✂️ Text pre-processing (tokenization, cleaning, encoding)  
- 🔢 Representing text as numbers  
- 🧱 Bag of Words and TF-IDF (implemented from scratch)  
- 📬 Spam detection using Bag of Words  
- 🧮 From term frequency to importance weighting  
- 📚 N-grams and context  
- 🧠 Word2Vec — understanding word meaning through vectors  
- ✨ Transition from representation to understanding  

Each section mixes **theory, code, and visual intuition** so you can follow the logic behind how NLP systems evolved.

---

## 🧪 Spin-Off Projects

This repo includes a few small, playful projects that build on ideas from the main notebook.

### 💬 Tamaras Hair  
A simple **rule-based chatbot** that mimics early heuristic NLP — a throwback to when AI systems were hand-crafted, not trained.  

📂 `Tamaras Hair/`

---

### ⚙️ Encoder PlayGround  
A simple **interactive interface** that encodes any input text into a chosen system — binary, hex, or octal.  
A “side quest” to show that **tokenization and numerical encoding** weren’t born with NLP; they’ve been with computing all along.

📂 `Text Encoder/Encoder-PlayGround/`

---

### 📚 Book Recommendation System  
A **TF-IDF + cosine similarity** based recommender built using the Goodreads dataset.  
- Pick a book from the gallery (Gradio app)  
- Get top-10 similar books instantly  
- See classic NLP still powering useful systems today  

📂 `Book recommendation system/`

---

## 🧩 Future Ideas
- Add support for **Swahili** or other African languages  
- Visualize **embedding spaces** interactively  
- Add a section on **Transformers** — just to complete the arc (GPUs are quite cheap 😄)

---

## 🛠️ Tech Stack
- **Python 3.12**
- NumPy, Pandas, scikit-learn, joblib  
- Gradio for the demos  
- Dataset: *Goodbooks* (via Goodreads)

---

## 💬 Final Thought
> *“If you can’t explain how machines understand language, build it until you can.”*

---

**Author:** [Morgan Thiuri](https://www.linkedin.com/in/morgan-thiuri-40151327a/)  
Data Scientist | Exploring NLP from first principles  
