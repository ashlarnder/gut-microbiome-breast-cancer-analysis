# gut-microbiome-breast-cancer-analysis
This repository includes R code for the analysis completed as part of my PhD work. We ran a case-control study in British Columbia, Canada, collecting data at enrollment (baseline) and follow-up. 

Data generated or analyzed during this study are not publicly available due to privacy considerations and risk of subject identification given the small group of participants.

## GMBC_baseline-analysis
This is the R code used for the analysis and plotting for the baseline data, when our participants were enrolled into the study. 
This code requires 7 datasets to be pulled in:
- Estrobolome_targets (this is a list of estrobolome targets identified in a previous paper:  https://doi.org/10.1002/ijc.35427)
- gmbc_data (this is the health, demographics, and dietary data collected via the CDHQIII)
- profiled_metagenome.tsv (MetaPhlAn relative abundances measured from stool)
- humann.path_nopipe.csv (HUMAnN3 pathway annotations measured from stool)
- humann.enzymes_nopipe.csv (HUMAnN3 enzyme annotations measured from stool)
- GMBC_Metabolite_Results.plasma.csv (targeted metabolomics panel measured in blood plasma)
- GMBC_Metabolite_Results.stool.csv (targeted metabolomics panel measured in raw stool)

## GMBC_longitudinal-analysis
