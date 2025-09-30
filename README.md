#  Alzheimer’s Disease Gene Expression Analysis (GSE5281)

##  Overview
This project analyzes gene expression data from the **GSE5281 dataset** (NCBI GEO) to identify transcriptional changes associated with Alzheimer’s disease (AD).  
The goal is to perform preprocessing, differential expression analysis, and biological interpretation to uncover potential biomarkers and pathways relevant to AD.  

---

##  Objectives
- Preprocess and normalize transcriptomic data  
- Identify differentially expressed genes (DEGs) between Alzheimer’s and control samples  
- Perform statistical tests and corrections for multiple testing  
- Visualize results using PCA and volcano plots  
- Highlight key genes and pathways associated with Alzheimer’s disease  

---

##  Dataset
- **Source**: NCBI GEO – [GSE5281](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5281)  
- **Type**: Microarray-based gene expression profiling  
- **Samples**: Postmortem brain tissues from Alzheimer’s patients and healthy controls  

---

## 🛠️ Tools & Libraries
- **Languages**: Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn, Scikit-learn)  
- **Bioinformatics**: GEOparse  
- **Visualization**: PCA plots, volcano plots  

---

##  Methodology
1. **Data Retrieval** → Downloaded GSE5281 dataset using GEOparse  
2. **Preprocessing** → Quality check, normalization, missing value handling  
3. **Exploratory Analysis** → PCA to observe sample grouping  
4. **Differential Expression Analysis** → log2 fold-change + t-test with multiple testing correction  
5. **Visualization** → PCA scatter plot, volcano plot of DEGs  

---

##  Results
- Identified differentially expressed genes (DEGs) between Alzheimer’s and control brain samples  
- PCA revealed separation between AD and Control groups  
- Volcano plot highlights upregulated and downregulated genes in AD  

---

##  Future Work
- Extend to other Alzheimer’s datasets (multi-cohort validation)  
- Integrate multi-omics data (proteomics, methylation)  
- Build machine learning models for AD vs. Control classification  

---

##  How to Run
### Google Colab
1. Open `Alzheimer_GSE5281.ipynb` in [Google Colab](https://colab.research.google.com/).  
2. Run all cells (dataset downloads automatically).  

### Local Jupyter Notebook
```bash
git clone https://github.com/your-username/Alzheimer-Gene-Expression-GSE5281.git
cd Alzheimer-Gene-Expression-GSE5281
pip install -r requirements.txt
jupyter notebook Alzheimer_GSE5281.ipynb
