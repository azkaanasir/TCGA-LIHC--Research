# TCGA-LIHC Transcriptomic Noise and Collinearity Analysis

## Project Overview
Analysis of gene expression **noise** (CV) and **collinearity** (VIF) in Liver Hepatocellular Carcinoma (LIHC) using TCGA data.

**Main Objective**: Identify genes and pathways where high variability and redundancy overlap, and validate findings using both threshold-based and unsupervised k-means methods.

## Key Results
- **Threshold method**: 123 candidate genes
- **k-means method**: 8 core Noise Conduction genes (complete overlap with threshold set)
- Strong signal in **Cytokine-cytokine receptor interaction** pathway
- Novel candidates distinct from known biomarkers (TP53, EGFR, etc.)

## Repository Structure
- `notebooks/` → Main analysis notebook (`transcriptomic_analysisCV_VIF.ipynb`)
- `results/` → Output tables and summaries
- `figures/` → Visualizations (CV vs VIF, cluster plots, pathway charts)


## How to Run the Analysis
1. Open `notebooks/transcriptomic_analysisCV_VIF.ipynb`
2. Run cells in order
3. All results and figures will be generated in their respective folders

## Next Steps (Discussion Points)
- Full pathway classification
- Multi-cancer comparison
- Survival analysis
- Functional annotation

---
