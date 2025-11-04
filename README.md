# Semi-Supervised Learning for Text Classification

**Research & implementation of semi-supervised learning methods for text classification using Python, TensorFlow, scikit-learn, and BERT.**  
Includes Self‑Training, Co‑Training, Cluster‑then‑Label, and GAN‑BERT approaches to improve performance when labeled data is limited.

---

## 📁 Repository Structure

| File / Notebook | Description |
|------------------|----------------------------|
| `SELF-TRAINING.ipynb` | Implementation and experiments for Self‑Training method |
| `CO-TRAINING.ipynb` | Implementation and experiments for Co‑Training |
| `ClusterThenLabel.ipynb` | Experiments using clustering then labeling approach |
| `GAN-BERT.ipynb` | GAN‑BERT approach combining GAN and BERT for semi-supervised learning |
| `README.txt` | (Old / backup readme) |
| `LICENSE` | License file (GPL‑3.0) |

---

## 🧠 Project Overview

Many NLP classification tasks (e.g. sentiment analysis, spam detection, hate‑speech detection) require large annotated datasets, which are expensive to build. This project explores how **semi-supervised learning** can leverage a small amount of labeled data together with abundant unlabeled data, to improve classification performance.

The implemented methods are:

- **Self‑Training** — using a base model to label unlabeled data iteratively  
- **Co‑Training** — two classifiers with different views teaching each other  
- **Cluster‑then‑Label** — clustering data and propagating labels  
- **GAN‑BERT** — combining GAN architectures with BERT for semi-supervised classification  

These are compared to **fully supervised baselines** to evaluate gains, data efficiency, and robustness.

---

## 🛠️ Tools & Technologies

- Python  
- Jupyter Notebooks  
- TensorFlow / Keras  
- scikit-learn  
- Hugging Face Transformers (BERT)  
- NumPy, pandas, matplotlib  

---

## Disclaimers
In the opening cells of every ipynb script, there are some cells that have
at the start comments which show what dataset will be downloaded and be processed
if we run this cell.

After these cells, there are explanations about certain lines of code as comments
