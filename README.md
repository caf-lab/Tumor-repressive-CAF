# Author : Seok-Hyung Kim M.D
Professor at Samsung medical center, department of pathology
college of medicine, Sungkyunkwan University

# Tumor-repressive-fibroblast subpopulation. 
Generallly activated fibroblasts and CAF (cancer associated fibroblasts) are known to promote tumor progression. However, some minor subpopulation of fibroblast is suspected to repress tumor progression and there is little known for this subpopulation. In this study, we searched for tumor repressive fibroblasts subpopulation in cancer tissue of colon cancer using single cell RNA/ATAC-seq data.

# Files required to run this code 
[1] /output/CRC_final_2022-09-05.rds : The processed file of E-MATB 7107 colorectal single cell data 
[2] /results/04.CRC_fbst_vs_all.other.cells.csv : Fibroblast-specific genes calculated based on single cell RNA-seq data
[3] /data/TCGA.colon.CA-survival.txt : Genes that are signicantly associated with colorectal cancer patients' survival based on TCGA data
[4] /data/CRC_expression_os.rda : TCGA colorectal cancer RNA-seq and survival files
[5] /signature/Human_iCAF_signature.xlsx
[6] /signature/Human_myCAF_signature.xlsx
[7] /signature/Human_mesCAF_signature.xlsx
[8] /signature/MSC_markers.csv
[9] /data/GSE114374_human_colon_fbst_geneset.RData
