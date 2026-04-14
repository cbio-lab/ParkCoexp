# Gene co‑expression networks and pathway activity

Weighted gene co‑expression network construction (WGCNA‑style via BioNERO) integrated with pathway activity inference (PROGENy).

🔗 **Access the full study report:** [Quarto report](http://download.ripcm.com/PARK2023/ParkCoexp/co-expression.html)

## Purpose
- Batch effect removal between laboratories (Moscow / St. Petersburg)
- Construction of signed hybrid networks (Pearson and Spearman correlations)
- Identification of co‑expression modules associated with:
  - mutation status (LRRK2, Parkin)
  - differentiation site
- Computation of module eigengenes (MEs)
- Correlation between MEs and signalling pathway activities (PROGENy)
- Visualisation: dendrograms, module eigengene heatmaps, gene‑level network plots (igraph)

## Requirements
- R (≥4.2)
- Packages: `decoupleR`, `dplyr`, `tibble`, `tidyr`, `purrr`, `stringr`, `ggplot2`, `pheatmap`, `vegan`, `pairwiseAdonis`, `DESeq2`, `limma`, `BioNERO`, `factoextra`, `ggpubr`, `ggdist`, `multcomp`, `RColorBrewer`, `DT`, `downloadthis`

## How to run
1. Clone the repository
2. Render `ParkCoexp.qmd`

## Data
Raw data: NCBI BioProject [PRJNA1346308](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA1346308/).

## Citation
*Convergent transcriptomic signature in iPSC-dopaminergic neurons of hereditary Parkinson's disease*  
DOI: (to be added after publication)

## License
MIT
