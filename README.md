# Product Recommendation System Using Text Embeddings

## 📌 Project Overview

This project implements a **content-based Product Recommendation System** that suggests relevant products by analyzing the semantic similarity between product descriptions and user-viewed items. The system uses **text embeddings** and **cosine similarity** to generate meaningful recommendations.

---

## 🧠 Methodology

1. Load and preprocess product data  
2. Combine product title and description  
3. Generate text embeddings for products  
4. Compute cosine similarity between viewed and non-viewed products  
5. Recommend the most similar products  
6. Visualize product clusters using PCA  

---

## 📥 Input

The input dataset contains product information:

- Product ID  
- Product Title  
- Product Description  

Each record represents one product.

---

## 📤 Output

- List of **recommended products**
- Product labels:
  - `recently_viewed`
  - `not_viewed`
  - `recommended`
- 2D visualization of product similarity clusters

---

## ⚙️ Techniques Used

- Text Embeddings for semantic representation  
- Cosine Similarity for recommendation  
- Principal Component Analysis (PCA) for visualization  

---

## 📈 Results & Observations

- Semantically similar products are clustered together  
- Recommended products appear close to recently viewed items  
- Embedding-based similarity provides better recommendations than keyword matching  

---

## 🛠 Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- OpenAI API (Text Embeddings)  
- Plotly  
- Jupyter Notebook  

---

## ▶️ How to Run the Project

1. Install dependencies:
```bash
pip install numpy pandas scikit-learn matplotlib plotly python-dotenv openai
