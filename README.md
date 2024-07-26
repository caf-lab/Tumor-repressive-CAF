# Author : Seok-Hyung Kim M.D
Professor at Samsung medical center, department of pathology
college of medicine, Sungkyunkwan University

# Tumor-repressive-fibroblast subpopulation. 
While activated fibroblasts and cancer-associated fibroblasts (CAFs) are well-known for promoting tumor progression, emerging evidence suggests the existence of a distinct fibroblast subpopulation with tumor-suppressive properties. However, our understanding of this subpopulation remains limited. This study aims to identify a tumor-repressive fibroblast subpopulation within colon cancer tissue using single-cell RNA and ATAC sequencing data.

# Files Required to Run the Analysis:
[1] /output/CRC_final_2022-09-05.rds : This file contains the processed single-cell RNA-sequencing data for colorectal cancer patients from study E-MATB 7107. 

[2] /results/04.CRC_fbst_vs_all.other.cells.csv : This file lists genes specifically expressed in fibroblasts based on the single-cell RNA-seq data.

[3] /data/TCGA.colon.CA-survival.txt : This file contains a list of genes significantly associated with colorectal cancer patient survival, derived from TCGA data. 

[4] /data/CRC_expression_os.rda : This file stores both the TCGA colorectal cancer RNA-sequencing data and corresponding survival information. 

[5] /signature/Human_iCAF_signature.xlsx : This Excel file likely contains a list of genes associated with iCAFs.

[6] /signature/Human_myCAF_signature.xlsx : This Excel file likely contains a list of genes associated with myofibroblast cancer-associated fibroblasts (myCAFs).

[7] /signature/Human_mesCAF_signature.xlsx : This Excel file likely contains a list of genes associated with mesothelial cancer-associated fibroblasts (mesCAFs).

[8] /signature/MSC_markers.csv : This CSV file likely contains a list of genes used to identify mesenchymal stem cells (MSCs).

[9] /data/GSE114374_human_colon_fbst_geneset.RData : This R data file contains multiple gene sets representing the subtype of colon fibroblasts from study GSE114374.

#### Note: These nine files are compressed into a single archive (8.3 GB). For access to this compressed file, please contact platoshkim@gmail.com. 
