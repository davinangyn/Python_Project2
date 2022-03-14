# Python_Project2

You will need a two files in order to adequately run the code:

  1. The jupyter notebook
  2. The TXT file that was used (uploaded here)

This project further analyzes how CPT-CEF treatment affects expression of genes in HT29 colon cancer cells. The control variable is the untreated HT29 cells (2 replicated samples), while the experimental variable is the treated HT29 cells (2 replicated samples). The bioinformatic method used in this project is pairwise alignment and differential expression analysis. Using the p-values obtained from the differential expression analysis, a volcano plot and heatmap were the two visual analysis methods performed. 

Information about where the gene count matrix file was found: The genes expressed in HT29 colon cancer cells when untreated and treated with CPT-CEF could be obtained from the NCBI GEO DB (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE165875). I imported the data file named "GSE165875_Processed_gene_abundance_matrix.txt" in which a different expression analysis was performed. The output of this code is a csv file containing a p-values of gene count dataframe from lowest to highest p-values. 

