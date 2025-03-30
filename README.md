# 📚 Building a RAG Model

## 🚀 Overview
This notebook demonstrates the implementation of a **Retrieval-Augmented Generation (RAG) model** to improve the accuracy of generated answers by incorporating external knowledge. The workflow involves:

✅ **Dependencies:** Installation of required packages such as `langchain` and `langgraph`.                                                 
✅ **Data Preprocessing:** Text is segmented and prepared using `langchain-text-splitters` for better retrieval.  
✅ **Model Implementation:** A RAG pipeline is developed to retrieve relevant documents and generate improved responses.  
✅ **Evaluation:** BLEU scores are calculated to assess the model’s performance before and after applying RAG.

---

## ⚡️ Installation
To install the required packages, run the following command:

```bash
pip install --quiet --upgrade langchain-text-splitters langchain-community langgraph
```

---

## 📖 Usage
1. **Open the Notebook:** Launch the `rag_model.ipynb` in Jupyter Notebook or Google Colab.
2. **Run All Cells:** Execute the cells sequentially to preprocess the data, implement the model, and evaluate results.
3. **Evaluate Results:** Compare BLEU scores to measure the improvement achieved by the RAG model.

---

## 📝 Notes
- The initial markdown section is titled **"Dependencies."**
- The first code cell installs necessary packages:
```python
%pip install --quiet --upgrade langchain-text-splitters langchain-community langgraph
```

---

## 📊 Results
The performance improvement is evaluated using BLEU scores:
- **Before RAG:** Baseline results without document retrieval.
- **After RAG:** Enhanced results by incorporating relevant information into the responses.

Happy Coding! 🎉
