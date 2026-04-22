# 🎬 Movie Recommendation System  
### Data Mining | Graph Analysis | BERT-Based NLP

---

## 📌 Overview

This project presents a **hybrid movie recommendation system** that combines multiple advanced techniques from data mining, graph theory, and natural language processing.

The system analyzes both:
- **User behavior (watch history)**
- **Movie content (descriptions & summaries)**

to generate accurate and intelligent recommendations.

---

## 🎯 Objectives

- Discover hidden patterns in user viewing behavior  
- Identify relationships between movies  
- Rank movies based on importance and influence  
- Analyze semantic similarity between movie descriptions  
- Build a **hybrid recommendation engine**  
- Provide meaningful insights through visualization  

---

## 🧠 Techniques Used

| Technique | Description |
|----------|------------|
| Association Rule Mining | Identify frequently co-watched movies |
| FP-Growth / Apriori | Extract frequent itemsets and rules |
| Graph Analysis | Model movie relationships as a network |
| PageRank / HITS | Rank movies by importance |
| BERT (NLP) | Analyze semantic similarity between movies |
| Data Visualization | Present insights clearly |

---

## 🏗️ System Architecture
```
Data Collection
↓
Data Preprocessing
↓
Pattern Mining (Apriori / FP-Growth)
↓
Graph Construction
↓
Link Analysis (PageRank / HITS)
↓
BERT Similarity Analysis
↓
Recommendation Engine
↓
Visualization & Insights
```

---

## 📁 Project Structure
```
movie-recommendation-system/
│
├── data/
│ ├── raw/ # Original datasets
│ └── processed/ # Cleaned and transformed data
│
├── notebooks/
│ ├── data_preprocessing.ipynb
│ ├── pattern_mining.ipynb
│ ├── graph_analysis.ipynb
│ ├── bert_analysis.ipynb
│ └── visualization.ipynb
│
├── outputs/
│ ├── frequent_itemsets.csv
│ ├── association_rules.csv
│ ├── pagerank_scores.csv
│ ├── similarity_matrix.csv
│ └── charts/
│
├── report/ # Final report (PDF)
├── presentation/ # Slides (PPT)
│
└── README.md
```

---

## ⚙️ Workflow Details

### 1️⃣ Data Collection & Preprocessing
- Load datasets (MovieLens, TMDb, etc.)
- Clean data:
  - Handle missing values
  - Remove duplicates
  - Standardize formats
- Transform:
  - Convert user history → transactions
  - Prepare text data for NLP

---

### 2️⃣ Pattern Mining
- Apply:
  - Apriori or FP-Growth
- Extract:
  - Frequent movie combinations
- Generate:
  - Association rules (Support, Confidence, Lift)

📌 Example: {Inception} → {Interstellar}

---

### 3️⃣ Graph Construction
- Build graph:
  - Nodes → Movies
  - Edges → Co-watching relationships
  - Weights → Frequency

---

### 4️⃣ Link Analysis
- Apply PageRank to:
  - Identify important movies
  - Rank influence in network

---

### 5️⃣ BERT-Based Analysis
- Convert movie descriptions → embeddings
- Compute similarity:
  - Cosine similarity
- Recommend:
  - Semantically similar movies

---

### 6️⃣ Recommendation Engine

The system combines 3 approaches:

#### ✔ Behavior-Based
- Based on association rules

#### ✔ Graph-Based
- Based on PageRank

#### ✔ Content-Based
- Based on BERT similarity

---

### 🔥 Hybrid Recommendation Formula

Final Score =
0.4 × Association Score +
0.3 × PageRank Score +
0.3 × BERT Similarity

---

## 📊 Outputs

- Frequent itemsets  
- Association rules  
- PageRank scores  
- Similarity matrix  
- Visual charts and graphs  
- Movie recommendations  

---

## 📈 Key Insights

The system can provide insights such as:

- Most popular movie genres  
- Frequently co-watched movie pairs  
- Influential movies in the network  
- Hidden relationships between movies  
- Semantic similarity trends  

---

## 🛠️ Technologies Used

| Category | Tools |
|--------|------|
| Data Processing | Pandas, NumPy |
| Pattern Mining | mlxtend |
| Graph Analysis | NetworkX |
| NLP | Transformers, Sentence-BERT |
| Visualization | Matplotlib, Seaborn, Plotly |
| ML Utilities | Scikit-learn |

---

## 🚀 How to Run the Project

1. Clone the repository
```bash
git clone <repo-link>
cd movie-recommendation-system
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Run notebooks in order:
data_preprocessing.ipynb
pattern_mining.ipynb
graph_analysis.ipynb
bert_analysis.ipynb
visualization.ipynb

⭐ Project Strengths
Combines multiple advanced techniques
Covers Data Mining + Graph Analysis + NLP
Real-world application (Recommendation Systems)
Highly scalable and modular
Strong academic and professional value

🔮 Future Enhancements
Build a web-based recommendation system
Deploy using FastAPI or Flask
Add user authentication
Implement real-time recommendations
Integrate deep learning recommendation models

📬 Conclusion

This project demonstrates how combining data mining, graph theory, and NLP can produce a powerful recommendation system capable of delivering accurate and meaningful insights.
