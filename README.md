# BRCA1-Variant-Landscape-Analysis
Analysis of BRCA1 variants from ClinVar — data cleaning, classification, and visualization of pathogenic vs benign distributions.

This project explores the landscape of clinical variants in the **BRCA1 gene** using publicly available data from [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/).  
It extracts BRCA1-specific variants, standardizes their clinical significance labels, and visualizes their distribution.

## 🚀 Key Features
- Extracts BRCA1 variants from ClinVar dataset (`variant_summary.txt`)
- Cleans and categorizes clinical significance into:
  - Pathogenic
  - Likely Pathogenic
  - Benign
  - Likely Benign
  - VUS (Uncertain Significance)
  - Other
- Exports cleaned dataset (`brca1_variants_cleaned.csv`)
- Generates visualizations:
  - 📊 Bar chart: counts of each classification  
  - 🥧 Pie chart: proportions of classifications  

## 📂 Repository Structure
