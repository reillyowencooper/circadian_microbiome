# Readme

This project contains code for:
Pfenning-Butterworth A.C, Cooper R.O., and Cressler C.E. _Diel rhythm influences microbiota composition in two zooplankton species._

Here, we examine the microbiota of two zooplankton species, _Daphnia magna_ and _Daphnia dentifera_. Though both species are freshwater zooplankton, they differ drastically in life history traits, including feeding preferences and migratory patterns. We looked at 16S rRNA sequences from both day and night samples from both species to see if we could find any taxa that may influence or be influenced by these life history differences.

Code for figure creation and data analysis is stored in the *scripts* directory. To run these R scripts, the following packages are required (sorted by install method):

CRAN
* [here](https://cran.r-project.org/web/packages/here/index.html)
* [phangorn](https://cran.r-project.org/web/packages/phangorn/index.html)
* [ggpubr](https://cran.r-project.org/web/packages/ggpubr/index.html)
* [tidyverse](https://cran.r-project.org/web/packages/tidyverse/index.html)
* [cowplot](https://cran.r-project.org/web/packages/cowplot/index.html)
* [rstatix](https://cran.r-project.org/web/packages/rstatix/index.html)
* [vegan](https://cran.r-project.org/web/packages/vegan/index.html)
* [stringi](https://cran.r-project.org/web/packages/stringi/index.html)
* [plyr](https://cran.r-project.org/web/packages/plyr/index.html)
* [parallel](https://www.rdocumentation.org/packages/parallel/versions/3.6.2)
* [gt](https://cran.r-project.org/web/packages/gt/index.html)

Bioconductor
* [dada2](https://benjjneb.github.io/dada2/dada-installation.html)
* [DECIPHER](https://bioconductor.org/packages/release/bioc/html/DECIPHER.html)
* [phyloseq](https://joey711.github.io/phyloseq/install.html)
* [microbiome](https://microbiome.github.io/tutorials/Installation.html)

Developer Github
* [speedyseq](https://github.com/mikemc/speedyseq)
* [DivNet](https://github.com/adw96/DivNet)

Data is stored in the *data* directory. A pre-processed .rds object that is the phyloseq output of the *process_16s.Rmd* script is included as *processed_16s_all.rds*, if you want to skip that entire step. Otherwise, you will need to download the dada2-formatted GTDB database, located [here](https://zenodo.org/record/3951383) to appropriately identify ASV taxonomy. 

I have not included the raw 16S read data in this project as they take up more space than Github allows, but will be adding the accession numbers once this project is submitted to NCBI.