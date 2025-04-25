# 🔍 TF-IDF Text Analysis & Search Engine

This project implements **TF-IDF (Term Frequency - Inverse Document Frequency)** from scratch to analyze text documents and rank them based on relevance to a search query using **Cosine Similarity**.

It includes:

- **Manual TF-IDF Calculation** (No external NLP libraries like scikit-learn or NLTK)
- **Document Frequency (DF)** and **Inverse Document Frequency (IDF)** computation
- **TF-IDF visualization** with bar charts for each document
- **Search functionality** to find the most relevant documents based on a query

---

## 📂 Project Structure

```
TF-IDF-Search-Engine/
│
├── documents/           # Folder containing text documents (doc1.txt, doc2.txt, ...)
├── tfidf_search.ipynb   # Main Jupyter Notebook with full code
└── README.md            # Project documentation
```

---

## 🚀 Features

- **TF-IDF Calculation:** Compute TF, DF, IDF, and TF-IDF scores for each document manually.
- **Visualization:** Generate bar plots of TF-IDF scores for each document.
- **Search Engine:** Use **Cosine Similarity** to rank documents based on a user-defined query.

---

## 📊 Example Outputs

### TF-IDF Table (sample):

|       | asthma | cancer | cholesterol | diabetes | heart |
|-------|--------|--------|-------------|----------|-------|
|doc1.txt| 0.000 | 0.000  | 0.000       | 0.0785   | 0.000 |
|doc2.txt| 0.000 | 0.000  | 0.000       | 0.000    | 0.0294|
|...    | ...    | ...    | ...         | ...      | ...   |

---

### TF-IDF Bar Chart (sample):

![Sample TF-IDF Bar Chart](sample_tfidf_plot.png)

---

### Search Example:

```bash
Query: "high blood pressure and heart disease"

Search Results:
1. doc2.txt: Similarity = 0.3105
2. doc3.txt: Similarity = 0.3012
3. doc4.txt: Similarity = 0.1008
...
```

---

## 🛠️ How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/TF-IDF-Search-Engine.git
cd TF-IDF-Search-Engine
```

2. **Add your `.txt` documents** to the `documents/` folder.

3. **Open `tfidf_search.ipynb` in Jupyter/Colab** and run the cells.

---

## ⚙️ Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

Install with:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## 📚 Concepts Covered

- **TF (Term Frequency)**  
- **DF (Document Frequency)**  
- **IDF (Inverse Document Frequency)**  
- **TF-IDF (Weighting Scheme)**  
- **Cosine Similarity** for document ranking  
- **Data Visualization** (bar charts for TF-IDF scores)

---

## 🤝 Contributions

Feel free to fork, submit issues, or contribute!

---
