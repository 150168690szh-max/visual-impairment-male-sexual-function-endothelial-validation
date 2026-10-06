# Visual impairment and male sexual dysfunction

## Systematic review, stratified evidence synthesis, and endothelial transcriptomic validation

This repository contains the reproducible analysis code, processed outputs, and documentation supporting the study:

**Visual impairment and male sexual dysfunction: a systematic review, stratified evidence synthesis, and endothelial transcriptomic validation**
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23147382.svg)](https://doi.org/10.5281/zenodo.23147382)

---

## Authors

- **Junquan Hu** — First author
- **Zihao Shi** — Co-first author
- **Zhisong Guo**
- **Juan Zhang**
- **Shenghuang Zhu** — Corresponding author

Junquan Hu and Zihao Shi contributed equally to this work.

---

## Project overview

This study integrates two complementary components.

### Work 1 — Clinical evidence synthesis

A systematic review and stratified evidence synthesis evaluating the association between visual impairment and male sexual dysfunction, including erectile dysfunction, erectile function, sexual activity, desire, and satisfaction.

Because the available studies differed substantially in visual-exposure definitions, outcome instruments, comparator structures, and effect measures, no single pooled overall effect estimate was calculated when clinically inappropriate.

### Work 2 — Endothelial transcriptomic validation

Publicly available transcriptomic and genetic datasets were analysed to investigate endothelial biological features relevant to erectile dysfunction.

The principal datasets include:

- **GSE206528** — human corpus cavernosum single-cell RNA sequencing
- **GSE261085** — human corpus cavernosum spatial transcriptomics
- **GSE2457** — diabetic rat penile tissue expression data
- **OpenGWAS ebi-a-GCST006956** — erectile dysfunction GWAS summary statistics

The omics analyses provide biological support and mechanistic context but are not intended to establish that visual impairment causes erectile dysfunction.

---

## Repository structure

```text
03_scripts/
    Main R analysis scripts.

04_results/
    GSE206528/
    GSE261085/
    GSE2457/
    ED_GWAS/
    cross_dataset/

05_figures/
    Main and supplementary analysis figures.
    marker_validation_figures/

05_reproducibility/
    audits/
    environment/
    TableS8/
