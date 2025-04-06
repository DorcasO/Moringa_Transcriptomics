# Moringa_RNASeq

## Overview
This repository contains transcriptomic bioinformatics scripts used in the analysis of RNA-Seq data for drought-responsive genes in *Moringa oleifera*. The workflow includes quality control, read alignment, differential expression analysis, weighted gene correlation network analysis (WGCNA), functional annotation, and visualization.

## Workflow
1. **Raw Data Processing**  
   - Quality control with FastQC & MultiQC  
   - Adapter trimming with Trimmomatic  

2. **Alignment**  
   - Mapping reads using HISAT2 or STAR  

3. **Differential Expression Analysis**  
   - Identifying DEGs using DESeq2 and edgeR  

4. **Weighted Gene Correlation Analysis**
   -identifying modules and hub genes

5. **Functional Annotation & Enrichment**  
   - GO term enrichment using clusterProfiler  
   - KEGG pathway analysis  

6. **Visualization**  
   - Volcano plots for DEGs  
   - GO term bar plots  

## Installation & Dependencies
- Install required bioinformatics tools:

Moringa_RNASeq/
│── raw_data_processing/
│   ├── quality_control.sh  # Script for FastQC & MultiQC
│   ├── trimming.sh         # Script for Trimmomatic
│── alignment/
│   ├── hisat2_mapping.sh   # HISAT2 alignment script
│   ├── star_mapping.sh     # STAR alignment script
│── differential_expression/
│   ├── deseq2_analysis.R   # DESeq2 script
│   ├── edger_analysis.R    # edgeR script
│── functional_analysis/
│   ├── go_enrichment.R     # GO term enrichment analysis
│   ├── kegg_analysis.R     # KEGG pathway analysis
│── visualization/
│   ├── volcano_plot.R      # DE visualization
│   ├── go_barplot.R        # GO term bar plots
│── docs/
│   ├── workflow_diagram.png  # Flowchart of the workflow
│   ├── results_summary.md    # Summary of key results
│── example_data/  # Optional example datasets
│── LICENSE
│── README.md
│── CONTRIBUTING.md
│── CHANGELOG.md
