# NB-CellScope

**Neuroblastoma Single-Cell Resource**

NB-CellScope is a research-facing web resource for exploring gene expression and cell-state heterogeneity in neuroblastoma (NB).

- **Live website (after cloud deployment):** https://danbioinfo.tech/nb-cellscope/
- **GitHub Pages landing (after enabling Pages):** https://magic136.github.io/NB-CellScope/
- **Underlying GEO dataset:** [GSE223374](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE223374)
- **Publication:** [Nian et al., *Frontiers of Medicine* (2024)](https://doi.org/10.1007/s11684-024-1081-7)

## Resource overview

The study comprises **15,447 single-cell profiles from 8 specimens and 6 patients**, including **two patients with matched primary and bone-marrow-metastasis specimens**. The deployed atlas is a reprocessed visualization of GEO data; its **19 clusters are not identical to the published study's six reported cell states**.

Available features on the hosted website include interactive UMAP visualization, gene-symbol search, per-sample and per-cluster filtering, data links, and publication references.

## How to access

Use the hosted website above for interactive gene queries. This GitHub repository provides **research descriptions, citations, resource links and a GitHub Pages entry point**, not the private server implementation or complete gene-expression database. GitHub Pages does not run Python/SQLite APIs.

## Citation

Nian Z, Wang D, Wang H, et al. Single-cell RNA-seq reveals the transcriptional program underlying tumor progression and metastasis in neuroblastoma. *Frontiers of Medicine*. 2024;18(4):690–707. https://doi.org/10.1007/s11684-024-1081-7

## Data availability

The study's count matrices and sample-level records are available in [GEO GSE223374](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE223374). Reprocessed UMAP and expression visualizations are provided through the hosted NB-CellScope platform.

## Project status

The GitHub repository and Pages URLs above are **planned addresses** until you create the `NB-CellScope` repository and enable Pages. The live website address requires cloud deployment before it can be used.
