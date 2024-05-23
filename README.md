# KO_availability through YCharOS Partners 
#This code is designed to identify the protein targets with CRISPR knockout (KO) lines available from YCharOS partners, including Abcam and Horizon. The script leverages knock-out cell line data downloaded from Cellosaurus (version 49, May 2024).

#Functionality
#Data Import: The script imports KO cell line information from Cellosaurus (Version 49, May 2024).
#Target Identification: It determines the number of unique protein targets that have one or more KO lines available.
#RNA Expression Filtering: The final step involves filtering these KO lines according to RNA expression data from the DepMap (23Q2 dataset from Broad Institute, 2023). This dataset, downloaded from DepMap (Broad Institute, 2023), includes data from CRISPR knockout screens from Project Achilles and genomic characterization data from the CCLE project.
