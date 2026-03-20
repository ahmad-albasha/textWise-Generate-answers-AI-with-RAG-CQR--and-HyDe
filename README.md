<div align="center">

<br/>

# 🧠 textWise
## AI-Powered Question Answering · RAG · CQR · HyDe

### Retrieval-Augmented Generation · Streamlit · OpenAI API

<br/>

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
[![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented-00C49A?style=for-the-badge)](https://github.com/ahmad-albasha/textWise-Generate-answers-AI-with-RAG-CQR--and-HyDe)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

<br/>

> *"Don't just search — understand."*

<br/>

---

</div>

## 🌟 Overview

**textWise** is an interactive question-answering application built with **Streamlit**, designed to give organizations and individuals a powerful AI-driven search experience over their **own data**.

It combines three cutting-edge NLP techniques to eliminate hallucinations and maximize retrieval precision:

| Technique | Role |
|---|---|
| 🔎 **RAG** — Retrieval-Augmented Generation | Grounds every answer in relevant retrieved documents |
| 🔄 **CQR** — Conversational Query Reformulation | Refines user queries for more accurate retrieval |
| 🧠 **HyDe** — Hypothetical Document Embeddings | Generates richer query embeddings for semantic matching |

Powered by the **OpenAI API**, textWise is highly adaptable for companies, students, schools, and research institutions that need AI-powered search over their own custom datasets.

<br/>

---

## 🚀 Features

| | Feature | Description |
|---|---|---|
| 📚 | **Custom Dataset Support** | Upload any documents or datasets; answers are grounded in your own knowledge base |
| 🔎 | **RAG-Powered Retrieval** | Responses backed by retrieved context — not hallucinations |
| 🔄 | **CQR — Query Reformulation** | Automatically improves user queries for more precise retrieval |
| 🧠 | **HyDe Embeddings** | Enhances semantic matching by generating hypothetical document embeddings |
| 🎨 | **Streamlit UI** | Clean, interactive, and user-friendly web interface — no frontend skills needed |
| 🔑 | **OpenAI API Integration** | Harnesses state-of-the-art LLMs for generation and embedding |
| 🌍 | **Scalable Use Cases** | Corporate knowledge bases · Academic tools · School platforms |

<br/>

---

## 🗂️ How It Works

```
👤 User Query
      │
      ▼
🔄 CQR — Conversational Query Reformulation
   (rewrite & clarify the query for better retrieval)
      │
      ▼
🧠 HyDe — Hypothetical Document Embedding
   (generate a hypothetical answer to enrich the query vector)
      │
      ▼
🔎 Vector Search over Custom Dataset
   (retrieve top-k semantically relevant chunks)
      │
      ▼
📄 Context Assembly
   (combine retrieved chunks into a coherent prompt)
      │
      ▼
🤖 OpenAI LLM — Answer Generation
   (generate a grounded, context-aware response)
      │
      ▼
💬 Final Answer → Streamlit UI
```

<br/>

---

## 🛠️ Installation

**1. Clone the Repository**

```bash
git clone https://github.com/ahmad-albasha/textWise-Generate-answers-AI-with-RAG-CQR--and-HyDe.git
cd textWise
```

**2. Install Dependencies**

```bash
pip install -r requirements.txt
```

**3. Set Your OpenAI API Key**

```bash
# Linux / macOS
export OPENAI_API_KEY="your_api_key_here"

# Windows (Command Prompt)
set OPENAI_API_KEY="your_api_key_here"

# Windows (PowerShell)
$env:OPENAI_API_KEY="your_api_key_here"
```

> 💡 Alternatively, create a `.env` file in the project root:
> ```
> OPENAI_API_KEY=your_api_key_here
> ```

**4. Run the App**

```bash
streamlit run app.py
```

Then open your browser at `http://localhost:8501` 🎉

<br/>

---

## 📁 Project Structure

```
textWise/
│
├── 📄 app.py                   # Main Streamlit interface & app logic
├── 📄 requirements.txt         # Project dependencies
├── 📄 README.md                # Project documentation
│
├── 📂 utils/                   # Core AI pipeline modules
│   ├── rag.py                  # Retrieval-Augmented Generation logic
│   ├── cqr.py                  # Conversational Query Reformulation
│   └── hyde.py                 # Hypothetical Document Embeddings
│
└── 📂 data/                    # Custom dataset files (your documents)
```

<br/>

---

## 🎯 Use Cases

<table>
  <tr>
    <td>🏢</td>
    <td><b>Companies</b></td>
    <td>Internal knowledge management, HR policy Q&A, employee onboarding assistants, and support automation.</td>
  </tr>
  <tr>
    <td>🎓</td>
    <td><b>Universities & Students</b></td>
    <td>Academic research assistants, thesis exploration tools, and intelligent study helpers.</td>
  </tr>
  <tr>
    <td>🏫</td>
    <td><b>Schools</b></td>
    <td>Interactive educational platforms for curriculum Q&A and subject-specific learning bots.</td>
  </tr>
  <tr>
    <td>🔬</td>
    <td><b>Research Institutions</b></td>
    <td>Literature review tools, paper summarizers, and dataset-aware AI assistants.</td>
  </tr>
</table>

<br/>

---

## 📦 Requirements

Install all dependencies via:

```bash
pip install -r requirements.txt
```

Key libraries:

| Library | Purpose |
|---|---|
| `streamlit` | Interactive web UI |
| `openai` | LLM & embedding API calls |
| `langchain` | RAG pipeline orchestration |
| `faiss-cpu` / `chromadb` | Vector store for retrieval |
| `tiktoken` | Token counting & text splitting |
| `python-dotenv` | Environment variable management |

<br/>

---

## 🤝 Contributing

Contributions are welcome and appreciated!

1. **Fork** the repository
2. Create a branch: `git checkout -b feature/your-improvement`
3. Commit your changes: `git commit -m "feat: describe your change"`
4. Push and open a **Pull Request** 🚀

**Ideas to explore:**
- [ ] Support for PDF, DOCX, and CSV document ingestion
- [ ] Add chat history and multi-turn conversation memory
- [ ] Integrate open-source LLMs (LLaMA, Mistral) as alternatives to OpenAI
- [ ] Add a document management dashboard
- [ ] Deploy to Streamlit Cloud or Hugging Face Spaces

<br/>

---
## 👤 Author

Ahmad Albasha

[![GitHub](https://img.shields.io/badge/GitHub-ahmad--albasha-181717?style=flat-square&logo=github)](https://github.com/ahmad-albasha)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/ahmad-a-9a0373123)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail)](mailto:ahmad-albasha09@hotmail.com)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

<br/>

---

<div align="center">

**Built with 🧠 intelligence, 🔎 precision, and ☕ late nights**

[![GitHub](https://img.shields.io/badge/GitHub-ahmad--albasha-181717?style=flat-square&logo=github)](https://github.com/ahmad-albasha/textWise-Generate-answers-AI-with-RAG-CQR--and-HyDe)

⭐ **If textWise helped you build smarter — give it a star!** ⭐

</div>
