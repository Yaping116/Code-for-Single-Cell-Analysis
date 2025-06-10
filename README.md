README

This repository contains the scripts for analyzing the snRNAseq library generated from mouse left ventricular samples in a chronic stress model, for the manuscript titled 'Single-nucleus profiling of the left ventricle of the mouse heart after chronic stress’.

Repository Scripts
This repository contains 3 scripts:

1.Single-sample cellcount analysis: This script runs cellranger count, the first step in single-cell RNA-seq data processing. It aligns sequencing reads to a reference genome, generates feature-barcode matrices, and performs basic filtering.

2.Integrated analysis of diverse CellRanger: This script runs cellranger aggr, which combines multiple single-cell RNA-seq samples (processed by cellranger count) into a single analysis-ready dataset with normalized counts.

3.Single sample Seurat analysis and multi sample integration analysis: R script for single sample Seurat analysis and multi sample integration analysis.
