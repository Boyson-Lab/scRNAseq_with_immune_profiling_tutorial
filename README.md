
# Boyson-lab Single Cell RNA Data Analysis with Immune Profiling Tutorial

Welcome to the Boyson-lab GitHub repository! This tutorial aims to provide a comprehensive guide to analyzing single-cell RNA sequencing (scRNA-seq) data with a focus on immune profiling. Whether you are new to scRNA-seq analysis or looking to enhance your existing skills, this tutorial will help you navigate the intricate world of single-cell transcriptomics.

## Introduction

In recent years, scRNA-seq has revolutionized our understanding of cellular heterogeneity and gene expression at the single-cell level. This powerful technique enables researchers to unravel the complexity of biological systems by capturing gene expression profiles from individual cells. Immune profiling using scRNA-seq has emerged as a crucial application, enabling in-depth investigations of immune cell populations, their states, and their responses in various biological contexts.

## Tutorial Overview

This tutorial is designed to guide you through the key steps of scRNA-seq data analysis, providing detailed explanations and practical examples along the way. Here's a brief overview of the analysis pipeline:

 <p align="center">
<img src="../img/sc_workflow_2022.jpg" width="600">
</p>

1. **Introduction to scRNAseq with immune repertoire profiling**: Explore how combining the scRNA-seq technique with immune repertoire profiling can enhance understanding of the diverse immune cell population. Gain knowledge on the technical aspects of scRNA-seq and how to effectively design an experiment to fully utilize this technique.

2. **Generate count matrix from sequence reads**: Learn how to convert raw scRNA-seq sequence reads into a count matrix with a simple step-by-step process. This matrix is essential for analyzing gene expression patterns, cell surface protein expression and TCR repertoire profiling at the single-cell level, using the Seurat R package.

3. **Custom analysis of TCR sequences**: Learn how to transform a TCR VDJ count matrix into a compatible format for merging with gene expression and cell surface protein count matrices in Seurat.

4. **Filter cells using quality metrics and demultiplex the hashtags**: Discover how to combine the gene expression, TCR, and cell surface protein datasets in Seurat, and filter the data to include only high-quality cells. Additionally, learn how to separate the cells into individual biological/technical replicates by utilizing the hashtag information for the cell surface proteins.

5. **Data normalization and clustering**: Learn the process of normalizing data, determining whether to integrate or not, and creating clusters specific to cell types.

6. **Cluster identification and gene expression visualization**: Learn how to identify the clusters of cell types by utilizing known marker genes and view the expression of specific individual genes or the combined expression of a group of genes.

7. **Differential gene expression and pseudo-bulk DGE analysis**: Learn how to conduct differential gene expression (DGE) analysis, which includes pseudo-bulk analysis, to pinpoint genes that display significant differential expression between experimental conditions or cell clusters.

8. **Trajectory analysis**: Learn how to conduct trajectory analysis with the SCANPY PAGA toolkit, which is based on Python.

9. **Custom analysis of TCR VDJ usage**: Learn how to effectively visualize the usage of TCR γ and δ-chain V-segments, identify the top paired CDR3 clonotypes within the dataset, and create CDRaa spectratype plots.



## Getting Started

To begin your journey into scRNA-seq analysis with immune profiling capabilities, simply follow each of the above steps (clickable) one after another. Each tutorial section is accompanied by code examples, interactive notebooks, and sample datasets, allowing you to follow along and practice the concepts discussed.

We hope this tutorial will empower you to harness the immense potential of scRNA-seq data for immune profiling studies. Enjoy exploring the fascinating world of single-cell transcriptomics and uncovering the intricacies of the immune system!

If you have any questions or feedback, please don't hesitate to reach out. Happy analyzing!