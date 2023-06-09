# Transcriptomics_of_cell_lines


# ANALYSIS OF TRANSCRIPTOMIC DATA OF CELL LINES INFECTED WITH SARS-COV-2 VIRUS


This repository contains code and files for gene expression analysis, including pseudobulk and Desingle analysis differential gene expression analysis, Gene Set Enrichment Analysis and miRNA analysis. The repository is organized into different sections, each corresponding to a specific analysis step. Below is a brief description of the contents of each section:

## Sections

### Pseudobulk Analysis (Section 0)
- **00_preprocessing_pseudobulk_Calu.ipynb**: Code for preprocessing pseudobulk data from Calu cell line.
- **01_preprocessing_pseudobulk_h1299.ipynb**: Code for preprocessing pseudobulk data from H1299 cell line.
- **02_Pseudobulk_Calu3.ipynb**: Code for pseudobulk analysis specific to Calu3 cell line.
- **03_Pseudobulk_h1299.ipynb**: Code for pseudobulk analysis specific to H1299 cell line.
- **0_Pseudobilk_DEGs**: Folder containing results of the pseudobulk analysis.

### Desingle Analysis (Section 1)
- **12_DEsingle_prep_h1299.ipynb**: Code for preprocessing data for Desingle analysis in H1299 cell line.
- **13_DEsingle_Calu3.ipynb**: Code for Desingle analysis in Calu3 cell line.
- **13_desingle_calu3.ipynb**: Code for Desingle analysis in Calu3 cell line (alternate version).
- **1_DESingle_DEGs**: Folder containing results of the Desingle analysis.

### Differential Gene Expression Analysis (Section 2)
- **21_dim_reduction_dyeing.ipynb**: Code for dimensionality reduction of the gene expression data and dyeing the cells by their expression levels of certain genes.
- **22_expression_barplots.ipynb**: Code for visualizing Log 2 Fold Changes of top genes identified by each method.

- **23_interscection_of_genes_by_two_methods.ipynb**: Code for identifying the intersection of differentially expressed genes obtained from pseudobulk and Desingle analysis.

### Enrichment Analysis of Pseudobulk-Obtained Genes (Section 3)
- **30_enr_pseudo_calu3_enrichment_maps.ipynb**: Code for enrichment analysis of pseudobulk-obtained genes specific to Calu3 cell line.
- **30_enrichment_functions_h1299.ipynb**: Code for enrichment analysis functions for pseudobulk data in H1299 cell line.
- **31_Enrichment_barplots_by_hrs_H1299_pseudobulk.ipynb**: Code for generating barplots of enrichment results for pseudobulk data in H1299 cell line.
- **31_enr_pseudo_Enrichment_barplots_by_hrs_Calu3_pseudobulk.ipynb**: Code for generating barplots of enrichment results for pseudobulk data in Calu3 cell line.
- **3_enrichment_pseudo**: Folder containing results of the enrichment analysis for pseudobulk-obtained genes.

### Enrichment Analysis of Desingle-Obtained Genes (Section 4)
- **40_enr_single_calu3_GSEA_map.ipynb**: Code for GSEA (Gene Set Enrichment Analysis) mapping for enrichment analysis of Desingle-obtained genes in Calu3 cell line.
- **41_Enrichment_barplots_by_hrs_H1299_single.ipynb**: Code for generating barplots of enrichment results for Desingle data in H1299 cell line.
- **42_enr_single_calu3_Enrichment_barplots.ipynb**: Code for generating barplots of enrichment results for Desingle data in Calu3 cell line.
- **4_enrichment_single**: Folder containing results of the enrichment analysis for Desingle-obtained genes.


### miRNA Analysis (Section 5)
- **50_trim_mirna.ipynb copy**: Code for trimming miRNA data.
- **51_mirna_preprocessing.ipynb**: Code for preprocessing miRNA data and retrieving isoforms.
- **52_mirna_deseq2.ipynb**: Code for miRNA Differential Expression Aanalysis using the DESeq2 package.
- **53_Calu3_mirna_enrichr.ipynb**: Code for Gene Set Enrichment Analysis of miRNA data in Calu3 cell line.
- **5_miR_results**: Folder containing results of the miRNA analysis.


### Full-scale images and additional code outputs are available https://drive.google.com/drive/folders/1QGpkX_4WeY3FUT5022_BUDkBmDPuBIwn?usp=share_link 
