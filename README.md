## 📝 SUMMARY – Text Summarization Using NLP

This notebook performs **text summarization** using Natural Language Processing techniques. It condenses long text documents into shorter summaries while preserving key information. It demonstrates both extractive and abstractive approaches depending on the method used.

### 🧠 Key Features
- Automatic summarization of long-form text  
- Preprocessing: tokenization, stopword removal, and cleaning  
- Uses NLP libraries like SpaCy, NLTK, or Transformers  
- Can handle user-input or preloaded text samples  
- Educational and modular notebook format  

### 📁 File
- `SUMMARY.ipynb` – Jupyter Notebook implementing summarization workflow

### ✅ Requirements
```bash
pip install numpy pandas nltk spacy sumy
python -m nltk.downloader punkt
python -m spacy download en_core_web_sm
