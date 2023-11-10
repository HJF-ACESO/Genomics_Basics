# Genomics_Basics

### Author: Pavol Genzor
Description of basic workflow for RNA-Seq analysis. The tools include practice working with basic R data types and packages including:
- data.table
- ggplot
- deseq2

The main markdown summarized two ways of approaching the differential gene expression analysis. 

- In the first case, the fold changes, mean values, p.values, and adjustments are done manually. This process is ideally applied to measurements that have been normalizing for sample variability - such as TPM or FPKM values.
- In the second case, the DESeq2 software performs normalization of the raw count data and calculates all the resulting values. This suite is well accepted in the field and is the preferred way to normalize raw count data or to evaluate various and even multiple hypotheses. 



