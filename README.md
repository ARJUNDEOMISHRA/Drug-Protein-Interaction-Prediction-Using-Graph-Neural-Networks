# Drug-Protein-Interaction-Prediction-Using-Graph-Neural-Networks


## 📌 Project Overview
This project focuses on predicting **Drug–Protein Interactions (DPI)** using
**Graph Neural Networks (GNNs)**.  
Both drugs and proteins are represented as graphs, allowing the model to learn
complex structural and relational patterns for accurate interaction prediction.

The system is designed as a **binary classification model** that predicts whether
a given drug and protein pair interact.

---

## 🎯 Objectives
- Represent drugs and proteins as graph structures
- Learn meaningful representations using Graph Neural Networks
- Predict drug–protein interactions accurately
- Explore different GNN architectures such as **GCN** and **GraphSAGE**

---

## 🧠 Key Concepts Used
- Graph Neural Networks (GNN)
- Drug–Protein Interaction (DPI)
- Molecular graph construction from SMILES
- Protein sequence graph modeling
- Binary classification
- Deep learning with TensorFlow

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Framework:** TensorFlow / Keras  
- **GNN Library:** Spektral  
- **Bioinformatics Tools:** RDKit, BioPython  
- **Other Libraries:** NumPy, Pandas, Matplotlib

---

## 📂 Dataset
The dataset contains:
- **Drug SMILES strings**
- **Protein amino acid sequences**
- **Interaction labels (0 / 1)**

Each drug–protein pair is converted into a **combined graph representation**
before being passed to the GNN model.

---

## 🧪 Methodology
1. Load drug–protein interaction data
2. Convert drug SMILES into molecular graphs
3. Convert protein sequences into graph representations
4. Combine drug and protein graphs into a single interaction graph
5. Train GNN models (GCN / GraphSAGE)
6. Evaluate performance on validation and test data

---

## 🧬 Model Architecture
- Graph Convolution layers (GCN / GraphSAGE)
- Dropout for regularization
- Global pooling layers (Average & Max)
- Fully connected layers
- Sigmoid output for binary classification

---

## 📊 Evaluation
- Training and validation loss
- Training and validation accuracy
- Binary classification performance metrics

---

## 📁 Project Structure
├── data/
│ ├── raw/
│ └── processed/
├── utils/
│ └── data_loader.py
├── models/
│ └── gnn_model.py
├── config.py
├── A 7semester project (4).ipynb
├── README.md
