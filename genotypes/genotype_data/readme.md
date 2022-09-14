# Readme for directory mckenzie_2021/genotypes/genotype_data/ 

### directories  

__main directory__: interemediate and final genotype files from 2022
__genemapper_output__: These are the raw genotype tables output by genemapper. 
__old_genotypes__: data from previous reports/manuscripts

### Files in the main directory (genotype_data)

__gt_0.1__: This is a wide format gentic dataset (no metadata) for all 2022 genotyping BEFORE re-runs were added.  
__gt_0.3__: re-runs incorporated, no metadata, no previous data, no filtering of any kind. wide format   
__gt_l_0.3__: re-runs incorporated, no metadata, no previous data, no filtering of any kind. long format  

__missing_genos...__ These files are used to fix some failed merging when combining old genotype data, new genotype data and the consolidated final metadata. No one should need to open these, but they are required to make the genotype prep notebook run smoothly (see genotype_data_prep notebook for details).

 
### Files in subdirectory "genemapper_ouptut"

These are the raw genotype tables output by genemapper. 
Note that plates 17-20 have a naming error in the raw files (see big mistake log). 

plates 29-30 and 31-29 are re-runs

### Files in subdirectory "old_genotypes"

__progeny_microsats__: 2017 Progeny query for microsat data. Also contains neatly organized (by tab) metadata for all samples 2007-2016. However note that the genotypic data has small differences from the dataset used in previous approaches, with a small number of different calls, but more commonly, genotypes that are missing in the data. Still no explanation on whether this is due to final data not being uploaded to progeny, or if re-runs were done after 2016 manuscript to fill missing data. Unlikely that the latter (re-runs) is the case though because these genotypes match a small subset files dated to 2014. It is the only source of genotype data after the 2016 manuscript (2016 and 2017 cougar trap samples), but before Dayan began genotyping in 2021.   
__id_key.txt__: used to match current sample ids to previous sample_ids  
__10APR2016_cougar_Adult__: This is the file used for the 2016 manuscript and tech reports for parentage assignment. USE THIS ONE.  
__04JAN2016_below_dam_cougar__: This file contains some additional samples used in 2016 tech report and manuscript, but excluded from the 10APR2016_cougar_adult dataset because they are carcass samples from below the dam.
