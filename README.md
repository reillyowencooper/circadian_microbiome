# Readme

This project examines the microbiota of two zooplankton species, _Daphnia magna_ and _Daphnia dentifera_. These species have fairly different life histories, and different feeding preferences during the day and night. Here, we looked at 16S rRNA sequences from both day and night samples from both species to see if we could find similarities and differences between species and between time points.

I have not included the raw 16S read data in this project, but will be adding the accession numbers and a script to download the files to the correct directory once the project is submitted to NCBI.

Currently, the *scripts* directory contains two files:
* *process_16s.Rmd*: This script processes the raw read files using the dada2 algorithm in R. It also assigns taxonomy using the latest GTDB database formatted for dada2. Then, it converts the taxonomy-labelled data to a phyloseq object for downstream statistics and visualization.
* *visualize_16s.Rmd*: Work in progress script to visualize aspects of the microbiota in both species. This is primarily done with phyloseq.