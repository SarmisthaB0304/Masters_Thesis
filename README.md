Clustering High-Dimensional Gene Expression Data: A Dose-Response Study with Valproic Acid (VPA)
This repository contains the code, data, and analysis for a thesis project focused on clustering high-dimensional dose-response gene expression data. 
The study evaluates the performance and stability of several unsupervised clustering algorithms in identifying patterns of gene expression across varying doses of valproic acid (VPA).

Project Overview
In the rapidly evolving field of genomics, understanding gene responses to different drug dosages is vital for the advancement of personalized medicine and targeted therapies. Clustering techniques, a core component of unsupervised machine learning, are used here to uncover meaningful biological patterns from complex gene expression data.

This project applies and compares five clustering algorithms:
K-Means
Hierarchical Clustering
DBSCAN
OPTICS
ORICC (Orthogonal Recursive Cluster Identification with Constraints)

Each algorithm is tested on both real-world and synthetic datasets to evaluate their robustness and stability in capturing biologically relevant gene expression patterns.

📁 Dataset
The primary dataset used in this project originates from Krug et al. (2013), which explores developmental neurotoxicity (DNT) using human embryonic stem cells (hESCs) treated with valproic acid (VPA).

Gene Expression Platform: GeneChip® Human Genome U133 Plus 2.0
Preprocessing: RMA (Robust Multi-Array Average)
Scale: log2-transformed expression values
Conditions: 8 VPA concentrations (0 mM to 1000 mM)
Replicates: 6 for control, 3 for each treatment concentration
Genes: 54,675
There are no missing values in the dataset, ensuring high data quality.

🎯 Objectives
Explore the dose-response relationship using visualizations like boxplots and PCA plots.
Apply five clustering algorithms on the VPA dataset.
Simulate datasets with varying characteristics to test algorithm stability.
Evaluate clustering performance using the Adjusted Rand Index (ARI).
Identify the most consistent and reliable algorithm across datasets.

🧪 Methods
Dimensionality reduction techniques (e.g., PCA)
Visualizations (Matplotlib, seaborn)
Clustering with different R packages and functions
Performance evaluation using ARI

📊 Key Findings
Clustering revealed groups of genes with similar responses to VPA doses, aiding in the identification of potential biomarkers and mechanisms of drug action.
The project demonstrated the comparative strengths of each algorithm, highlighting one or more as robust candidates for real-world gene expression analysis.

💡 Significance
This study provides:

A benchmark comparison of clustering techniques for gene expression analysis
Insights into gene regulatory mechanisms in response to drug treatments
A foundation for future research in bioinformatics, toxicogenomics, and computational biology



