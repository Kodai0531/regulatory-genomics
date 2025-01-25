# **Regulatory Genomics**

This repository contains Jupyter notebooks from my assignments in the course **"Comparative and Regulatory Genomics"**, as part of my **MSc in Bioinformatics** program at **KU Leuven, Belgium**. The analyses focus on **bulk RNA sequencing (RNA-seq) and chromatin immunoprecipitation sequencing (ChIP-seq)** to study transcriptional and regulatory changes in Parkinson’s disease (PD).

## **Contents**

### **1. Bulk RNA-seq Analysis (`BulkRNA_seq.ipynb`)**
This notebook presents a **differential gene expression analysis** of the **substantia nigra** between **healthy controls** and **Parkinson’s disease (PD) patients** using **bulk RNA-seq** data. The workflow includes:

- **Quality Control (QC)** of raw sequencing reads.
- **Read alignment** to the reference genome (hg38).
- **Gene quantification** using featureCounts.
- **Differential expression analysis** using DESeq2.
- **Functional enrichment analysis** (GO term and pathway analysis) to identify biological processes associated with the differentially expressed genes.
- **Visualization of results**, including MA plots, volcano plots, and heatmaps.

### **2. ChIP-seq Analysis (`ChIP_seq.ipynb`)**
This notebook focuses on **ChIP-seq data analysis** for **THAP1**, a transcription factor implicated in PD, to investigate its role in the regulation of **alpha-synuclein (SNCA)** gene expression. The workflow includes:

- **Quality Control (QC)** of raw sequencing reads.
- **Read alignment** to the human genome (hg19).
- **Peak calling** using **MACS2** to identify THAP1 binding sites.
- **Genome-wide coverage visualization** using **bigWig** files in **IGV**.
- **Motif discovery** to identify potential **THAP1 binding motifs**.
- **Functional enrichment analysis** to associate THAP1-bound regions with relevant biological pathways.


## **References**
- **Bulk RNA-seq Study:** [Xicoy H et al., 2020](https://pmc.ncbi.nlm.nih.gov/articles/PMC7564986/)
- **ChIP-seq Study:** [Cheng et al., 2022](https://doi.org/10.1093/brain/awac001)

## **Author**
**Kodai Tsurumi**  
MSc in Bioinformatics, KU Leuven  

---
