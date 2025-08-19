textWise

textWise is an interactive question-answering application built with Streamlit.
It leverages advanced Retrieval-Augmented Generation (RAG) techniques, along with CQR (Conversational Query Reformulation) and HyDe (Hypothetical Document Embeddings), powered by the OpenAI API, to generate accurate and context-aware answers from custom datasets chosen by the developer.

This makes textWise highly adaptable for companies, students, schools, and research institutions that need AI-powered search and answering systems over their own data.

🚀 Features

📚 Custom Dataset Support: Developers can upload their own documents or datasets for knowledge-grounded answers.

🔎 RAG-powered Retrieval: Ensures responses are backed by relevant data instead of hallucinations.

🔄 CQR (Conversational Query Reformulation): Improves user queries for more precise retrieval.

🧠 HyDe (Hypothetical Document Embeddings): Enhances semantic matching by generating richer query embeddings.

🎨 Streamlit UI: A simple, interactive, and user-friendly web interface.

🔑 OpenAI API Integration: Utilizes the power of state-of-the-art LLMs.

🌍 Scalable Use Cases: Suitable for corporate knowledge bases, academic learning tools, and school projects.

🛠️ Installation

Clone this repository:

git clone https://github.com/your-username/textWise.git
cd textWise


Install dependencies:

pip install -r requirements.txt


Add your OpenAI API key as an environment variable:

export OPENAI_API_KEY="your_api_key_here"


Run the Streamlit app:

streamlit run app.py

📂 Project Structure
textWise/
│── app.py                # Main Streamlit interface
│── requirements.txt      # Dependencies
│── utils/                # Helper functions for RAG, CQR, HyDe
│── data/                 # Custom dataset files
│── README.md             # Project documentation

🎯 Use Cases

🏢 Companies: Internal knowledge management and employee Q&A tools.

🎓 Universities & Students: Academic research assistance and study helpers.

🏫 Schools: Educational platforms for interactive learning.

🤝 Contribution

Contributions are welcome! Feel free to submit pull requests or open issues to improve textWise.
