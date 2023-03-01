# mckenzie_2022
Using Genetic Pedigrees to Evaluate McKenzie Spring Chinook Salmon Reintroduction

# Summary

This is a complete repository for the 2022 McKenzie Spring Chinook Salmon Reintroduction Project. All data and code to reproduce or extend this project are available here. It includes results pertaining to potential offspring from 2010 - 2020 and candidate parents from 2007 - 2017.   

Each major directory has a detailed readme that explains the files within.  

The repository is formatted to be opened as an RStudio project.   

# Repository and Archive

The repository is version controlled on github at https://github.com/david-dayan/mckenzie_2022 .

Some versions of the repository are published and archived on zenodo. All versions are available at the stable link https://doi.org/10.5281/zenodo.7651591

# Notebooks

Notebooks are interactive files that can be opened in a browser (.html), or used to run code in Rstudio (.Rmd).

I chose to break up the analyses into multiple notebooks rather than a single, giant unwieldy one. All notebook run from available files in this repository, but if you want to reproduce results from scratch using the raw genotypes you'll need to run the following notebooks in order. 

(1) cougar_trap_metadata_mgmt  
(2) meta_data_consolidation  
(3) genotype_data_prep  
(4) parentage_notebook  
(5) analysis_notebook


# Directories  

(1) __Analysis__: All analyses including demographic and genetic results, fitness modeling and figures needed for the report and main mansucript. Notebooks detailing other analyses targeted for publication in other manuscripts, such as fitting animal models to estimate heritability, tracing readaptation, etc, are located in different repositories.   
(2) __Genotypes__: All genetic data, raw and processed, from previous workers and from the present genotyping. Contains it's own detailed readme within.  
(3)  __Lab Work__: DNA extraction and plating logs, microsatellite amplification, ABI templates, re-runs, tissue inventory.  
(4) __Metadata:__ Raw and processed sample metadata (and some genetic data too...) from both current project (Dayan) and previous. Contains it's own detailed readme within.  
(5) __Notes__: Minutes from important meetings and emails, additional analyses, scattered thoughts, etc.   
(6) __Parentage__: Directory for all work to assign offspring to parents, given finalized genotypes.  
(7) __QGIS__: NOT BACKED UP TO GITHUB. Files for making a pretty map.  
(8) __Report Drafts__: All drafts and of the USACE report.   
(9) __Main Manuscript__: Drafts, revisions, and information needed to submit the main evaluation manuscript.  



