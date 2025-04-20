⚕️ Personalized Adverse Drug Reaction Prediction using Heterogeneous GNNs
This project predicts personalized adverse drug reactions (ADRs) using a Heterogeneous Graph Neural Network (GNN) trained on curated biomedical datasets including SIDER and CTD. The graph includes entities such as drugs, genes, diseases, and side effects, and uses multi-relational edge types to learn rich embeddings for link prediction between drugs and side effects.

🔧 Features
  Parses and preprocesses real-world biomedical datasets (SIDER, CTD)
  Builds a multi-relational heterogeneous graph using PyTorch Geometric
  GNN model with GAT-based HeteroConv layers for entity representation
  Link prediction head to identify potential drug–side effect associations
  Evaluation metrics: ROC-AUC, AUPRC
