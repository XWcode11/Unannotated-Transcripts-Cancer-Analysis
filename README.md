## Data Access

**📊 Complete Dataset on Zenodo:**

- [Zenodo Repository](https://doi.org/10.5281/zenodo.17766620)

## Folder Structure

1. The CombatCorrected folder contains the cell line expression matrices and differential analysis results after ComBat batch effect correction.
   DEG_three_methods_function.R is the main script for differential analysis, containing three differential analysis methods: DESeq2, edgeR, and limma-voom.
   run_combat-DEanalysis.R is the script that calls this function, specifically designed for processing ComBat-corrected data.
2. Tissues-DATA contains expression matrices and differential analysis results for tissue samples. The differential analysis method uses DEG_three_methods_function.R, without ComBat correction.
