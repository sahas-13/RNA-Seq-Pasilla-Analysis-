# RNA-Seq Analysis of Pasilla Gene Depletion in Drosophila melanogaster

## Overview
This project performs reference-based RNA-Seq analysis to identify 
differentially expressed genes after depletion of the Pasilla gene 
in Drosophila melanogaster.

## Dataset
- Source: Brooks et al. 2011
- 4 untreated samples + 3 treated samples
- GEO accession: GSE18508
- Raw data: https://zenodo.org/record/6457007

## Methods
1. Quality Control (Falco + MultiQC)
2. Trimming (Cutadapt)
3. Mapping (RNA STAR, dm6 genome)
4. Read Counting (featureCounts)
5. Differential Expression (DESeq2)
6. GO Enrichment Analysis (FlyEnrichr)
7. KEGG Pathway Analysis (FlyEnrichr)

## Key Results
- 789 significantly differentially expressed genes (padj < 0.05)
- Top downregulated gene: FBgn0039155
- Top upregulated gene: FBgn0025111
- Key pathways: ECM-receptor interaction, Glycolysis

## Tools Used
- Galaxy platform (usegalaxy.org)
- Falco v1.2.4
- Cutadapt v5.2
- RNA STAR v2.7.11b
- featureCounts v2.1.1
- DESeq2
- FlyEnrichr

## Tutorial Reference
Galaxy Training Network: Reference-based RNA-Seq data analysis
https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/ref-based/tutorial.html
