# GoGreen
## Zhongjie, Erik, Beth, and McKena
### Group A

### Research question: What SNPs may be responsible for differential expression in the Wisconsin Diversity Panel. 

Task 1: Discover the genes that are most differentially expressed across the Wisconsin Diversity Panel 

   Previous studies by Hart et al. (2013) and Wagner et al. (2012), delineate the importance of standardizing RNA-seq gene expression data. Our group chose to convert the denoted FPKM values to TPM values in order to account for gene length and sequencing depth. To normalize the TPM values across genes within each cultivar, Z score was calculated. To determine which genes were differentially expressed, the variance of zTPM scores across the 942 lines was calculated for each gene. The genes with a variance score of 45 and above were selected. This group represents the top 1.5% of genes in the initial dataset. 
   
   SNPs found within the subset of high differential expression represent 0.45% of the original SNP matrix. This subset of data was then analyzed with MatrixeQTL in order to determine the SNPs most highly correlated to the gene expression values.
   
_Experimental Flow_

- FPKM --> TPM
- TPM --> zTPM
- Variance of zTPM
- Top 1.5% of variance scores
- Isolate SNPs within top 1.5% of genes
- Run MatrixeQTL
   
 
- I just edited this markdown (Erik)
- A second edition, now done locally from my PC (Erik)

A third, separate ~deleted~. E
Let's now say that somebody else modify this file. 


Adding in some info (Beth): I have tried to install Git locally on my computer, but have been unsucessful. I have played around on the github website and feel comfortable with making branches and submitting pull requests. 

So we add overall info here in the READ.ME correct? Then just code in our folders?

NEED TO ADD CITATIONS FOR PAPERS LISTED IN FIST PARAGRAPH
