# Analysis of single-cell RNA sequencing data in R
This is a pipeline to analyse single-cell RNA sequencing data from neurons (1) isolated from acute midbrain slices of transgenic mice using visually guided aspiration via patch pipettes and (2) processed using SMART-seq2.

## Resources used
This pipeline has been generated after attending the [EMBL-EBI RNA-Sequence Analysis Course](https://www.ebi.ac.uk/training/events/2019/rna-sequence-analysis) and [attending](https://training.csx.cam.ac.uk/bioinformatics/event/2823386) and following the online course on [Analysis of single cell RNA-seq data](https://github.com/hemberg-lab/scRNA.seq.course) by the [Hemberg Lab](https://www.sanger.ac.uk/science/groups/hemberg-group). Many other resources have been used, including the [Orchestrating Single-Cell Analysis with Bioconductor book](https://bioconductor.org/books/release/OSCA/) by Robert Amezquita, Aaron Lun, Stephanie Hicks, and Raphael Gottardo, the [simpleSingleCell workflow in Bioconductor](https://bioconductor.org/packages/3.9/workflows/html/simpleSingleCell.html) maintained by Aaron Lun, the [rnaseqGene workflow](https://bioconductor.org/packages/3.10/workflows/html/rnaseqGene.html) maintained by Michael Love, the [RNAseq123 workflow](https://bioconductor.org/packages/3.10/workflows/html/RNAseq123.html) maintained by Matthew Ritchie, and the [EGSEA123 workflow](https://bioconductor.org/packages/3.10/workflows/html/EGSEA123.html) maintained by Matthew Ritchie.

Other key resources include [Bioconductor](http://www.bioconductor.org/) (Huber et al., Nature Methods 2015), [scRNA-tools](https://www.scrna-tools.org/), `scater` (McCarthy et al., Bioinformatics 2017), `scran` (Lun et al., F1000Res 2016), `SC3` (Kiselev et al., Nature Methods 2017), `Seurat` (Butler et al., Nature Biotechnology 2018), `clusterExperiment` (Risso et al., PLOS Computational Biology 2018), `limma` (Ritchie et al., Nucleic Acids Research 2015), `DESeq2` (Love et al., Genome Biology 2014), `edgeR` (Robinson et al., Bioinformatics 2010), `MAST` (Finak, McDavid, Yajima et al., Genome Biology 2015), `iSEE` (Rue-Albrecht & Marini et al., F1000Research 2018), `t-SNE` (van der Maaten & Hinton, Journal of Machine Learning Research 2008), `UMAP` (McInnes et al., arXiv 2018), and the [Mathematical Statistics and Machine Learning for Life Sciences](https://towardsdatascience.com/tagged/stats-ml-life-sciences) column by Nikolay Oskolkov.

## Pre-required installation and necessary packages
To go through this pipeline, you will need to install the following: [R3.6.1](https://cran.r-project.org/) | [RTools35](https://cran.r-project.org/bin/windows/Rtools/) | [RStudio 1.1.463](https://www.rstudio.com/products/rstudio/download/) | [Git](https://git-scm.com/) | [Bioconductor 3.10](https://www.bioconductor.org/install/).

## List of notebooks
Mostly completed:
* [Part I: from a gene expression matrix to a SingleCellExperiment object](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part1.Rmd)
* [Part II: pre-processing and data quality control](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part2.Rmd)
* [Part III: normalization](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part3.Rmd)
* [Part IV: modelling technical noise and feature selection](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part4.Rmd)
* [Part V: batch correction and dimensionality reduction](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part5.Rmd)
* [Part VI: clustering](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part6.Rmd)
* [Part VII: differential expression analysis](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part7.Rmd)

Under development:
* [Part VIII: data visualisation](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_Part8.Rmd)

Other notebooks:
* [Possibly useful plotting tools](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_PlottingDevel.Rmd)
* [Code scraps](https://github.com/opavon/PAG_scRNAseq_analysis/blob/master/PAG_scRNAseq_analysis_scraps.Rmd)
