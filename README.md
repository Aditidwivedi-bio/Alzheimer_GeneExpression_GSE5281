# Gene Expression Analysis of Alzheimer's Disease (GSE5281)

This project analyzes the GSE5281 microarray dataset from the Gene Expression Omnibus (GEO)  
to identify differentially expressed genes between Alzheimer's disease and control brain samples.

## 📌 Objectives
- Load and preprocess public microarray gene expression data  
- Perform exploratory analysis using PCA  
- Identify differentially expressed genes (t-test)  
- Visualize results with a Volcano plot  

## 📊 Workflow
1. **Data Loading:** Downloaded GSE5281 using GEOparse  
2. **Data Cleaning:** Removed missing values and prepared expression matrix  
3. **Exploratory Analysis:** PCA to visualize sample clustering  
4. **Differential Expression:** t-test to identify significant genes  
5. **Visualization:** Volcano plot for significant genes  

## 🛠️ Tools & Libraries
- Python  
- GEOparse  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy, scikit-learn  

## 📈 Results
- PCA shows partial separation between Alzheimer's and control samples  
- Multiple genes with significant differential expression  
- Volcano plot highlights potential biomarker candidates  

## 📂 Dataset
- **Dataset ID:** GSE5281  
- **Source:** [NCBI GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5281)  

## 📌 Conclusion
This analysis demonstrates a beginner-friendly approach to working with public gene expression data  
and provides a foundation for more advanced bioinformatics workflows.
