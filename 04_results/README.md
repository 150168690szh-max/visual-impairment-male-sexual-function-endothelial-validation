# Processed results

This directory contains processed result tables and derived outputs used in the reproducible analyses.

## Directory structure

### `GSE206528/`
Processed results from human corpus cavernosum single-cell RNA-seq analysis.

Includes:
- cell-type annotation;
- endothelial-state summaries;
- ACKR1- and SELE-related analyses;
- donor-level statistics;
- endothelial marker tables;
- key-gene expression summaries.

### `GSE261085/`
Processed results from human corpus cavernosum spatial-transcriptomic analysis.

Includes:
- spatial clustering and annotation;
- endothelial marker summaries;
- ACKR1/SELE spatial association analyses;
- neighbourhood-enrichment results;
- first- and second-ring spatial enrichment;
- QC summaries.

### `GSE2457/`
Processed results from diabetic rat penile-tissue transcriptomic analysis.

Includes:
- differential-expression summaries;
- gene- and probe-level limma results;
- target-gene analyses;
- leave-one-out sensitivity analyses;
- sample information.

### `ED_GWAS/`
Processed results from the erectile-dysfunction GWAS analysis.

Includes:
- basic QC summary;
- genome-wide significant variants;
- distance-based significant loci;
- suggestive variants;
- top-ranked variants.

### `cross_dataset/`
Cross-dataset analyses linking GSE206528 endothelial signatures with GSE261085 spatial transcriptomics.

Includes:
- transferred endothelial signatures;
- anchor signatures;
- state-composition summaries;
- confidence summaries;
- transfer-threshold sensitivity analyses.

## Notes

Raw expression matrices, full GWAS summary statistics, and large processed R objects are not stored in this directory.

Large processed objects may be archived separately in a versioned Zenodo release.