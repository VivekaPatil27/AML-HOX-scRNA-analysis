# HOX/MEIS Epigenetic Regulator Analysis in AML

Single-cell RNA-seq analysis of CRISPR perturbation screen targeting epigenetic 
regulators of HOX/MEIS expression in acute myeloid leukemia.

## Dataset
- **GEO Accession:** GSE217779
- **Source:** Deshpande Lab, Sanford Burnham Prebys Medical Discovery Institute
- **Technology:** 10X Genomics Chromium Single Cell 3' v3 + CROPseq
- **Cells:** ~18,000 U937 AML cells with CRISPR perturbations

## Scientific Question
How do different epigenetic regulators (DOT1L, ENL, SGF29, AFF2, etc.) control 
HOX and MEIS1 expression in AML?

## Status
🚧 In progress (March 2026)

## Methods
- QC and cell filtering
- Normalization and clustering (Seurat)
- Perturbation analysis (compare KO vs control)
- HOX/MEIS expression analysis

## Project Structure
```
├── data/           # Raw and processed data
├── scripts/        # R analysis scripts
├── results/        # Figures and tables
└── README.md
```

## Contact
Viveka Patil  
MS Bioinformatics, Northeastern University