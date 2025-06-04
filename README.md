
# 📰 BBC News Topic Modeling with BERTopic & LDA

This project explores **topic modeling** on the **BBC News dataset** using two advanced techniques: **BERTopic** and **Latent Dirichlet Allocation (LDA)**. The goal is to uncover hidden topics within categorized news articles and compare the performance of transformer-based and probabilistic approaches.

---

## 📁 Dataset

- **Source**: [BBC News Classification Dataset](kaggle)
- **Description**: Consists of ~2,200 news articles across **5 categories**:
  - Business
  - Entertainment
  - Politics
  - Sport
  - Tech

---

## 🧠 Topic Modeling Techniques

### 1. BERTopic (Transformer-based)
- Embedding Model: `all-mpnet-base-v2` (Sentence Transformers)
- Dimensionality Reduction: **UMAP**
- Clustering: **HDBSCAN**
- Representation: **Maximal Marginal Relevance (MMR)**

### 2. Latent Dirichlet Allocation (LDA)
- Vectorization: **CountVectorizer / TfidfVectorizer**
- Model: **Gensim LDA**

---

## 🚀 How to Run

1. Open the provided `.ipynb` notebook (Google Colab or Jupyter Notebook).
2. Make sure you have the necessary libraries installed:
   ```bash
   pip install bertopic sentence-transformers hdbscan umap-learn gensim pyLDAvis
