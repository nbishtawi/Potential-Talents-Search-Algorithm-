# Talent Search Algorithm with NLP  

## Overview  
**Talent Search Algorithm** is a natural language processing (NLP) project designed to identify and rank potential candidates based on job titles and keywords. The project applies text similarity methods (TF-IDF, cosine similarity, and word embeddings) to match candidates with relevant opportunities.  

Note: The candidate dataset and GloVe embeddings are **not included** in this repository due to size and licensing restrictions.  
 
---

## Goals  
- Develop an algorithm to match **job candidates** to target keywords.  
- Use **NLP methods** (tokenization, embeddings, similarity measures) to capture semantic meaning.  
- Provide a scalable framework for **talent identification** in recruitment.  

---

## Features  
- **Data Preprocessing:** Tokenization of job titles with NLTK.  
- **Similarity Metrics:**  
  - TF-IDF with cosine similarity.  
  - Word embeddings (GloVe 300d) with semantic averaging.  
- **Custom Talent Search:** Match candidate job titles against specified keywords.  
- **Reproducibility:** End-to-end workflow in Jupyter notebooks.  

---

## Methodology  
1. **Data Loading** – Candidate job titles loaded from CSV.  
2. **Keyword Processing** – Input keywords tokenized with NLTK.  
3. **Text Representations** –  
   - TF-IDF vectors built from job titles.  
   - Embedding averages created using GloVe 300d vectors.  
4. **Similarity Calculation** –  
   - Cosine similarity for TF-IDF vectors.  
   - Embedding-based distance metrics for semantic closeness.  
5. **Ranking** – Candidates ranked by similarity to target keywords.  

---

## Results  
- Algorithm successfully matched candidates to relevant roles based on both lexical and semantic similarity.  
- Embedding-based approaches captured context better than TF-IDF alone.  
- Results demonstrate potential for **recruitment automation and candidate search**.  

---

## Tools & Technologies  
- **Python**  
- **Pandas, NumPy** – data processing  
- **NLTK** – tokenization and text processing  
- **Scikit-learn** – TF-IDF and similarity metrics  
- **GloVe embeddings** – semantic similarity representation  

