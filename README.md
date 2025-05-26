# Gene_Expression_Cancer

🧬 Cancer Subtype Classification using Gene Expression Data
This study explores the use of Machine Learning (ML) and Deep Learning (DL) models to classify different cancer subtypes based on gene expression patterns. We leverage models like SVM, Random Forest, Gradient Boosting, 1D CNN, and Graph Neural Networks (GNN) and perform clustering, feature selection, and dimensionality reduction for deep molecular insight and accuracy.

📂 Dataset
Source: ICMR dataset via Kaggle

Samples: ~802 patients

Cancer Types:

BRCA: Breast Cancer

KIRC: Kidney Renal Cancer

COAD: Colon Cancer

LUAD: Lung Cancer

PRAD: Prostate Cancer

Features: ~20,000 genes per patient

🧪 Techniques Used:

🔍 Preprocessing
Handling missing values, scaling, cleaning, and transformation

Dimensionality reduction using PCA

🔗 Clustering
K-Means

Hierarchical Clustering (Ward’s Linkage)

🧠 Models
Model	Accuracy
1D CNN	99.38%
GNN	98.76%
SVM	97.9%
Gradient Boosting	97.9%
Random Forest	97.5%

🔬 Deep Learning Models
🧩 1D Convolutional Neural Network (CNN)
2 Conv layers (16 & 32 filters) + MaxPooling

Adam Optimizer, CrossEntropy Loss

Validation Accuracy: 99.38%

🧠 Graph Neural Network (GNN)
2 GCN layers + Adam optimizer

Learns relational features from patient graphs

Validation Accuracy: 98.76%

🎯 Classification Models
SVM: Excellent generalization, ~97.9% accuracy

Random Forest: Highlighted key genes with interpretability, ~97.5% accuracy

Gradient Boosting: High performance, slightly lower precision

📊 Results & Visuals
Dimensionality Reduction: PCA reduced 20,000 → 530 features

Clustering: Separated data into cancer-specific clusters

Feature Selection: ANOVA identified significant genes (e.g. gene_9651)

Model Evaluation: Precision, Recall, F1-Scores above 0.93 for most models




This study demonstrates the powerful synergy between machine learning, deep learning, and bioinformatics in classifying cancer subtypes based on gene expression data. By leveraging advanced models like 1D CNN and Graph Neural Networks, we achieved high accuracy in detecting distinct cancer types. Feature selection techniques such as ANOVA helped uncover key genes potentially linked to disease mechanisms. Clustering methods revealed meaningful genetic patterns across samples, enhancing our biological understanding.

The models not only show strong performance but also offer valuable insights into molecular signatures, supporting the development of early diagnostic tools and personalized treatments. Future work can expand on this by integrating multi-omics data, applying transfer learning, and exploring causal inference methods to further boost clinical relevance and interpretability.
