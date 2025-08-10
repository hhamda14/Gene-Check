# 🧬 GeneCheck
**Lightweight Protein Family Classification for Real-World Impact**

## 🚀 Overview
AlphaFold changed biology by predicting protein structures with stunning accuracy — but it needed massive datasets and huge compute power.  

**GeneCheck** flips the script: we’re building a **lightweight AI** that can classify proteins into structural or functional families **using smaller datasets, fewer parameters, and faster training times**.  
Perfect for situations where compute is limited but accuracy still matters — like early-stage drug discovery or field research.

---

## 🎯 What We’re Building
- **Input**: Amino acid sequence
- **Output**: Predicted protein family + confidence score
- **Bonus**: Visualizations of secondary structures or binding affinities

---

## 🔹 Core Features (MVP)
1. **Data Ingestion & Preprocessing**  
   - Load sequences from public datasets (UniProt, PDB, Pfam)  
   - Clean, tokenize, and normalize

2. **Lightweight Model Training**  
   - ≤50M parameters (CNN, RNN, or small Transformer)  
   - Option to fine-tune **ESM-2** or **ProtBERT**

3. **Evaluation & Visualization**  
   - Accuracy, precision, recall, F1  
   - Graphical outputs for easy interpretation

---

## 🌟 Stretch Goals
- **Generative protein structures** via diffusion models  
- **Interactive web/notebook demo** for instant predictions

---

## 🧠 Modeling Approaches
- **Pre-trained embeddings**: [ESM-2](https://github.com/facebookresearch/esm), [ProtBERT](https://huggingface.co/Rostlab/prot_bert)  
- **Custom classifiers**: Small CNNs/RNNs for secondary structure prediction  
- **Generative**: Diffusion models for plausible 3D conformations

---

## 📂 Project Structure




---

## ⚙️ Quick Start
```bash
# Clone repo
git clone https://github.com/your-username/genecheck.git
cd genecheck
```

## 📊 Metrics
- **Accuracy**
- **Precision / Recall / F1-score**
- **Top-K Accuracy**

## 🛠 Tech Stack
- **Python** 3.10+
- **PyTorch** / **TensorFlow**
- **Hugging Face Transformers**
- **Biopython**
- **Matplotlib** / **Seaborn**

## 🤝 Credits
- **Meta AI** — [ESM-2](https://github.com/facebookresearch/esm)
- **RostLab** — [ProtBERT](https://huggingface.co/Rostlab/prot_bert)
- **Kaggle** — Dataset sources
- **AlphaFold** — Inspiration for GeneCheck
