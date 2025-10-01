# Rail Defect Classification using BERT

Applied NLP and machine learning to automate defect notification classification for Queensland Rail, improving maintenance reliability and decision-making.

## 📌 Project Overview
This research project focused on automating the classification of rail defect notifications using **semantic analysis and BERT embeddings**.  
The solution supports rail engineers by reducing manual effort, improving defect categorisation accuracy, and enabling predictive maintenance strategies.

## 🔬 Methods
- **Data preprocessing:** Text cleaning, tokenisation, embedding generation.
- **Model development:** Fine-tuned **BERT** for supervised defect classification (Ballast, Rail, Sleepers, Track Geometry).
- **Clustering:** Applied **K-Means** on BERT embeddings for unsupervised semantic grouping.
- **Evaluation:** Accuracy, F1-score, and clustering quality metrics to benchmark improvements.

## 📂 Repository Structure
- `notebooks/`
  - `Final_training_BERT.ipynb` → fine-tuning and evaluation of BERT classifier.
  - `Clustering Based on Semantic Similarity.ipynb` → semantic embeddings + K-Means clustering experiments.

## 🚀 Results
- Achieved **high-accuracy classification** of defect categories using BERT.
- Improved semantic clustering compared to keyword-only methods.
- Demonstrated potential for **real-world deployment** in rail maintenance decision systems.

## 🛠️ Tech Stack
- Python (pandas, NumPy, scikit-learn, PyTorch, transformers)
- NLP (BERT embeddings, tokenisation)
- Clustering (K-Means)
- Jupyter Notebooks

## 📖 Citation
If referencing this work:
> Ryenchindorj, S. (2024). Automating Rail Defect Classification using Semantic Analysis. Queensland University of Technology.

---

## 📌 Note
Due to confidentiality agreements, the full Queensland Rail dataset cannot be shared. This repo contains **code and sample workflows** for academic demonstration only.
