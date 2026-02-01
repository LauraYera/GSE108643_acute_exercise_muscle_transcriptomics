# Transcriptomic response of skeletal muscle to acute exercise (GSE108643)

This repository contains the code and supporting files used as a technical annex for a Master’s Thesis (TFM) in Bioinformatics.

The analysis focuses on the transcriptomic response of human skeletal muscle to acute exercise using publicly available RNA-seq data.

## Dataset
- GEO accession: **GSE108643**
- Subset: normal-weight subjects
- Design: paired pre vs post acute exercise (n = 14)

## Repository structure
- `rmarkdown/`: RMarkdown file containing the full analysis workflow
- `results/`: output tables generated from the analysis (DEGs, GO and KEGG results)
- `figures/`: figures used in the TFM (PCA, volcano plots, heatmaps, dotplots)
- `data/`: supporting data and metadata used in the analysis

## Analysis overview
- Exploratory analysis and quality assessment
- Principal Component Analysis (PCA)
- Differential expression analysis using limma
- Functional enrichment analysis (GO and KEGG)
- Data visualization

## Notes
The original raw data are publicly available from the Gene Expression Omnibus (GEO).
This repository is intended to provide transparency and reproducibility of the analyses performed in the TFM.
