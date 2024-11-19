# OmicGsea

## Introduction
In many omics datasets, such as Illumina DNA methylation data, genes are often represented by variable numbers of correlated probes, and a single probe may map to multiple genes. This complex data structure poses significant challenges for gene set enrichment analysis. The OmicGsea package addresses these challenges by providing both threshold- and ranking-based competitive enrichment analysis methods, effectively accounting for probe correlation and probe number bias. These versatile functions can be applied to a wide range of omics datasets, including DNA methylation, proteomics, genotyping, and genome sequencing. Additionally, the package includes a fast and accurate ranking-based enrichment method specifically designed for gene expression and RNA-seq data.

## Functions

<ul>
<li>`gseaGene()`:  Gene set enrichment analysis based on gene level combined p-values</li>
<li>`gseaPG()`:  Gene set enrichment analysis based on combined probe group p-values</li>
<li>`gseaProbe()`:  Gene set enrichment analysis based on probe level p-values</li>
<li>`gseaRank()`:  Ranking-based set enrichment analysis based on gene level p-values</li>
</ul>
