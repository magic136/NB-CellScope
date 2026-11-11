# NB-CellScope

> **Neuroblastoma Single-Cell Atlas & Gene Expression Explorer**

[![Publication](https://img.shields.io/badge/Study-Frontiers%20of%20Medicine%202024-326bb5?style=flat-square)](https://doi.org/10.1007/s11684-024-1081-7)
[![GEO](https://img.shields.io/badge/GEO-GSE223374-4a82cb?style=flat-square)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE223374)
![Cells](https://img.shields.io/badge/Cells-15%2C447-159994?style=flat-square)
![Samples](https://img.shields.io/badge/Samples-8-6172bd?style=flat-square)
![Website](https://img.shields.io/badge/Website-Preparing%20launch-8897a7?style=flat-square)

## 🌐 Online Platform

**NB-CellScope web application:** [https://danbioinfo.tech/nb-cellscope/](https://danbioinfo.tech/nb-cellscope/)  
*The website is being prepared for public launch; this GitHub repository is its project introduction.*

## 🧬 Overview

**NB-CellScope** is an interactive research resource for exploring gene expression and cellular heterogeneity in **neuroblastoma (NB)**, with a focus on primary tumors and bone-marrow metastases.

| Research cohort | Resource |
| :-- | :-- |
| **15,447** single-cell profiles | Unified UMAP and gene expression views |
| **8** tumor specimens from **6** patients | Sample-aware data exploration |
| **2** matched primary–metastatic pairs | Primary / metastasis comparison |
| **19** reprocessed clusters | Exploratory cluster-level views |

## 🔬 Main Features

- **Gene Expression Explorer** — Search a gene symbol to view normalized expression on a unified UMAP.
- **Interactive Atlas** — Filter cells by sample, tumor site, and reprocessed cluster; export UMAP images.
- **Research Reference** — Find the published starter-cell signature and key transcriptional programs.
- **Data Resources** — Browse NB single-cell studies, original publications, and public dataset links.

> **Data interpretation:** The unified atlas was independently reprocessed from GEO count matrices. Its 19 clusters do **not** correspond one-to-one to the six malignant cell states reported in the original study.

## 📖 Featured Publication

Nian Z, Wang D, Wang H, et al. **Single-cell RNA-seq reveals the transcriptional program underlying tumor progression and metastasis in neuroblastoma.** *Frontiers of Medicine*. 2024;18(4):690–707.  
**DOI:** [10.1007/s11684-024-1081-7](https://doi.org/10.1007/s11684-024-1081-7)

## 📂 Data Availability

The study's public expression count matrices and sample-level records are deposited in **[GEO: GSE223374](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE223374)**.

This repository is a project summary and citation page, similar to EGFR-MutSentry; it does **not** host the complete expression database, Seurat RDS files, or backend server. The resource is intended for research use and is not a clinical diagnostic service.
