# Analysis scripts

This directory contains the main R scripts used for the reproducible analyses.

The scripts are intended to be run in numerical order.

## Script order

### 01_GSE206528_download_QC.R
Downloads or prepares the GSE206528 single-cell RNA-seq dataset and performs initial quality-control processing.

Main tasks include:
- data import;
- sample and metadata inspection;
- quality-control metric calculation;
- filtering of low-quality cells;
- generation of the initial Seurat object.

### 02_GSE206528_celltype_annotation.R
Performs clustering and broad cell-type annotation for GSE206528.

Main tasks include:
- dimensionality reduction;
- clustering;
- marker-gene identification;
- broad cell-type annotation;
- identification of endothelial cells.

### 03_GSE206528_endothelial_states.R
Performs endothelial-cell subanalysis in GSE206528.

Main tasks include:
- endothelial subclustering;
- endothelial-state annotation;
- ACKR1-associated identity analysis;
- SELE-associated activation-state analysis;
- group-level endothelial-state comparisons.

### 04_GSE261085_spatial_processing.R
Processes the GSE261085 human corpus cavernosum spatial-transcriptomic dataset.

Main tasks include:
- spatial-data import;
- quality control;
- spatial clustering;
- expression normalisation;
- generation of spatial analysis objects.

### 05_GSE261085_signature_transfer_neighbourhood.R
Evaluates transcriptomic signature transfer and local spatial organisation in GSE261085.

Main tasks include:
- transfer of endothelial-state signatures;
- ACKR1- and SELE-related spatial analyses;
- neighbourhood definition;
- permutation-based spatial-enrichment analysis.

### 06_GSE2457_and_ED_GWAS.R
Performs complementary analyses using GSE2457 and erectile-dysfunction GWAS data.

Main tasks include:
- diabetic rat penile-tissue transcriptomic analysis;
- pathway and gene-expression summaries;
- erectile-dysfunction GWAS quality-control summaries;
- genome-wide significant locus characterisation.

## Data availability

Raw GEO data and full GWAS summary-statistics files are not stored in this repository.

The analyses use publicly available datasets including:

- GSE206528
- GSE261085
- GSE2457
- OpenGWAS `ebi-a-GCST006956`

Large processed R objects are excluded from GitHub and may be archived separately in a versioned repository.

## Reproducibility

Package versions, session information and audit files are provided in:

```text
../05_reproducibility/
