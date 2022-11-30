
## *Environmental drivers of demography and potential factors limiting the recovery of an endangered marine top predator*

#### *Ecosphere*

#### Amanda J. Warlick, Devin S. Johnson, Tom S. Gelatt, Sarah J. Converse

##### Please contact the first author for questions about the code or data: Amanda J. Warlick (awarlick@uw.edu)
_______________________________________________________________________________________

## Abstract

1. We fit mark-resight data to a Bayesian multi-event model to examine mechanisms linking environmental conditions to population dynamics and inform conservation measures for an endangered top predator: the Steller sea lion. 
2. The first demographic estimates for Steller sea lions in regions where abundance continues to decline indicate low male pup and female juvenile survival. 
3. Pup survival was positively correlated with the North Pacific Gyre Oscillation during the study period. 
4. This work can advance efforts to identify factors driving regionally divergent abundance trends, with implications for population-level responses to future climate variability. 

### Table of Contents

### [Scripts](./scripts)

+ SSL_CJS_CHdata.Rmd creates capture histories from raw data.
+ SSL_CJS.Rmd contains code for running models.
+ SSL_demographic_analysis_figs.R creates summary objects for inline references and figures.  
 
### [Data](./data) 

Contains raw and processed data.

### [Results](./results)

Contains raw and processed results.  

### [Figures](./figures)

Contains pdf versions of all figures in manuscript. 

### Required Packages and Versions Used 

here_1.0.1
dplyr_1.0.5
nimble_0.12.1
lubridate_1.7.20
reshape2_1.4.4
hmisc_4.5-0

### Details of Article 

Warlick AJ, DS Johnson, TS Gelatt, and SJ Converse. 2022. Environmental drivers of demography and potential factors limiting the recovery of an endangered marine top predator. Ecosphere 2022:e4325. https://doi.org/10.1002/ecs2.4325. 

### How to Use this Repository 

Begin by running the code chunks in SSL_CJS_CHdata.Rmd to create the capture histories from the raw data. Use SSL_CJS.Rmd to run models and SSL_demographic_analysis_figs.R to create summary objects for inline references and figures. 
