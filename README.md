# Alzheimer’s Disease Gene Expression — GSE5281

A clean, interview-ready notebook that downloads **GSE5281** from GEO, performs basic QC, PCA, and a simple differential expression analysis (AD vs Control if labels are present).

## How to run
1. Open in Google Colab or local Jupyter.
2. Run the cells top-to-bottom. The first cell installs dependencies.
3. Outputs (CSV results, plots) are saved in `outputs/`.

## Dependencies
- GEOparse, pandas, numpy, matplotlib, seaborn, scipy, scikit-learn, statsmodels

## Files
- `GSE5281_AD_analysis_polished.ipynb` – main analysis
- `outputs/` – generated results (created on run)
- `data/` – GEO cache (created on run)

## Notes
- Metadata parsing is heuristic; for publication-grade results add explicit curation and model-based DE (e.g., limma) with covariates (age, sex, region).
- Created: 2025-08-22
