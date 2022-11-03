# Diserge
Differentially Stably Expressed single cell RNA-seq Genes


Thanks for reading this introduction of Diserge: Differentially Stably Expressed single cell RNA-seq Genes. 🤗

In each single cell RNA-seq data (scRNA-seq) data, each cell expresses different types of genes in different amounts. 
The cellular average expression(CAE), the average expression of all kinds of genes that each cell expresses is also going to be different.

The concept of "stability" of gene in this package refers to expression similar to cellular average expression in a scRNA-seq.

This idea followed the idea of a housekeeping gene, a widely known concept in molecular biology.

To calculate the amount of gene stability in each scRNA-seq data, we compare two single cell values.

- Pk: the amount of each gene expressed in each cell.
- Qk: the average amount of all genes expressed in each cell.

