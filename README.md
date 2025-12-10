# Global and local genetic correlation reveals shared genetic architecture between congenital heart disease and neurodevelopmental disorders

Author(s): Daniel Linares, Beatriz Luna

## Description

Determine the genomic relationship between Congenital Heart Disease (CHD) and Neurodevelopmental Disorders (NDD). To this end, we use High Definition Likelihood (HDL) and Local Analysis of [co]Variant Association (LAVA).

This repository contains all the code used for this purpose. The following R Markdown Notebooks can be found here:

-   GWAS Meta-analysis METAL: It has the code to import GWAS summary statistics from FinnGen and the UKBB for the CHD phenotypes and run the meta-analysis using METAL.
-   HDL Genome-Wide Genetic Correlation: It has the code to import the METAL Meta-analysis results and import GWAS summary statistics from PGC for the NDD phenotypes, then perform Genome-wide Genetic Correlation.
-   LAVA Local Genetic Correlation: It has the code to import the METAL Meta-analysis results and import GWAS summary statistics from PGC for the NDD phenotypes, then perform Local Genetic Correlation.

Note: At the time the code is incomplete.
