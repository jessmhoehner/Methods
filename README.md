# Methods
A selection of the analytical processes and tools we use to provide rigorous, reproducible, and actionable results to our clients. If you are interested in a project with EICC please contact us via email at eicc@emory.edu or call us at (404) 778-5123

# RNA-Seq (bulk) Methods

## DESeq2
A demonstraton of the R/Bioconductor package DEseq2 to perform differential expression analysis from RNA-Seq count data. DESeq2 primarily uses the Wald test to determine differential expression between comparison groups.

## baySeq (in progress)
A demonstraton of the R/Bioconductor package baySeq to perform differential expression analysis from RNA-Seq count data. baySeq uses empirical Bayes methodology to estimate prior and posterior likelihoods of differential expression between comparison groups.

## edgeR
A demonstraton of the R/Bioconductor package edgeR to perform differential expression analysis from RNA-Seq count data. edgeR primarily uses the quasi-likelihood F test to determine differential expression between comparison groups.

# Microbiome Methods

## 16s analysis with phyloseq and LDM
A demonstartion of the R packages phyloseq and LDM. phyloseq takes in data from data processing programs like QIIME, mothur, and Pyrotagger. While QIIME2 offers richness estimates and other exploratory data analysis (ex: alpha and beta diversity metrices) we believe that phyloseq in combination with ggplot2 offers greater flexibility for generating customizable data visualizations. Once exploratory data analysis in phyloseq is complete, we use the LDM package to perform statistical analyses. LDM takes in a table of operational taxonomic units (OTUs) or amplicon sequence variants (ASVs) along with a table of data about the samples (i.e. covariates) and uses a linear decomposition model to associate experimental conditions and covariates of interest with microbial abundance.

# Miscellaneous

## False Discovery Rate Estimation with qvalue
A demonstraton of the R/Bioconductor package qvalue to estimate global and local false discovery rates from p-values and test statistics calculated from  differential expression analysis.

## Power & Sample Size Assesment for RNA-Seq with PROPER (in progress)
A demonstration of the R/Bioconductor package PROPER which uses simulation of experimental design constraints to provide guidance on how many people each comparison group needs for sufficient statistical power.
