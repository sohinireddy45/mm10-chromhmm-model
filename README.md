# mm10 Retina ChromHMM Model (Realigned Aldiri et al. 2017 Data)

This repository provides a ChromHMM chromatin state model for the **developing mouse retina**, constructed using publicly available ATAC-seq and ChIP-seq data from [Aldiri et al., 2017](https://www.sciencedirect.com/science/article/pii/S0896627317303483?via%3Dihub). We **realigned the original sequencing data to the mm10 genome (GRCm38)** and trained a **15-state ChromHMM model** to annotate functional chromatin states across key developmental time points.

All input data is derived from Aldiri et al. and no new experiments were performed.

---

##  Summary

- **Genome**: mm10 (GRCm38)
- **Source Data**: Aldiri et al., *Neuron* 2017
- **Assays**: ATAC-seq, ChIP-seq 
- **Developmental Stages**: E14.5 to A11
- **Tool Used**: ChromHMM v1.22
- **Output**: 12-state chromatin model, segmentations, and browser-ready tracks

---



