# Tutorial_chipseq

This project was conducted as a guided learning and reproducibility study based on a public ChIP-seq tutorial by Tommy Tang. The primary goal is to implement a complete end-to-end ChIP-seq analysis workflow using real public data. In addition, this project aims to reproduce publication-quality result visualizations similar to those reported in the original journal article, including signal tracks, peak profiles, and genome browser-style figures.

## Dataset

1. GEO accession: GSE66081
2. SRA accession:SRR1810900, SRR1810907, SRR1810912, SRR1810918

## Analysis workflow

1. FASTQ download using SRA toolkit.
2. Quality control using FastQC
3. Alignment to reference genome (Bowtie2)
4. BAM processing using SAMtools
5. Peak calling using MACS2
6. Peak annotation and visualizatio

## Tools Used
- SRA Toolkit
- FastQC
- Bowtie2
- SAMtools
- MACS2
- deepTools
- Python, Bash

## Reference
This project is inspired by and adapted from the following ChIP-seq tutorial:
- Tommy Tang, *Reproducing Genomic Paper Figures*
