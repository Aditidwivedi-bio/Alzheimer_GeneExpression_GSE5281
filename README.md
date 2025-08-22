Alzheimer’s Disease Gene Expression Analysis (GSE5281)
📌 Project Overview

This project focuses on analyzing gene expression data from the GSE5281 dataset (GEO) to identify transcriptional changes associated with Alzheimer’s disease (AD). The goal is to perform preprocessing, differential expression analysis, and biological interpretation to uncover potential biomarkers and pathways relevant to AD.

🎯 Objectives

Preprocess and normalize transcriptomic data.

Identify differentially expressed genes (DEGs) between Alzheimer’s and control samples.

Perform statistical tests and corrections for multiple testing.

Visualize results using heatmaps, volcano plots, and PCA.

Highlight key genes and pathways associated with Alzheimer’s disease.

🧬 Dataset

Source: NCBI GEO - GSE5281

Type: Microarray-based gene expression profiling.

Samples: Postmortem brain tissues from Alzheimer’s patients and healthy controls.

⚙️ Tools & Technologies

Languages: Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn)

Bioinformatics: GEOparse, gProfiler, Enrichr for pathway enrichment.

Visualization: PCA plots, heatmaps, volcano plots.

📊 Methodology

Data Retrieval: Downloaded GSE5281 dataset from GEO.

Preprocessing: Quality check, normalization, missing value handling.

Exploratory Analysis: PCA and clustering to observe sample grouping.

Differential Expression Analysis: Statistical testing with FDR correction.

Functional Analysis: Pathway and GO enrichment of significant genes.

Visualization: Heatmaps, volcano plots, boxplots of selected genes.

🔑 Key Results

Identified differentially expressed genes (DEGs) between Alzheimer’s and control brain samples.

Pathway analysis revealed enrichment in neurodegeneration, synaptic signaling, and inflammatory response pathways.

Visualizations highlight clear clustering between AD and control groups.

🚀 Future Work

Extend to other Alzheimer’s datasets (multi-cohort validation).

Integrate multi-omics data (proteomics, methylation).

Build a machine learning model for classification of AD vs. control.
