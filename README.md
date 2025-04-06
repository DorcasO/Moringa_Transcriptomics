# Moringa_RNASeq
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
