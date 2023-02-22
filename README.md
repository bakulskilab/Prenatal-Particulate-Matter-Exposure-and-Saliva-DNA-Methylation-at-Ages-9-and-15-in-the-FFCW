# Prenatal Particulate Matter Exposure Is Associated with Saliva DNA Methylation at Age 15: Applying Cumulative DNA Methylation Scores as an Exposure Biomarker

## Citation Information

Bakulski, K. M., Fisher, J. D., Dou, J. F., Gard, A., Schneper, L., Notterman, D. A., Ware, E. B., & Mitchell, C. (2021). Prenatal Particulate Matter Exposure Is Associated with Saliva DNA Methylation at Age 15: Applying Cumulative DNA Methylation Scores as an Exposure Biomarker. Toxics, 9(10), 262. https://doi.org/10.3390/toxics9100262. PMID: 34678958

This Github repository contains the data management and analytic scripts to produce the following manuscript: [Prenatal Particulate Matter Exposure Is Associated with Saliva DNA Methylation at Age 15: Applying Cumulative DNA Methylation Scores as an Exposure Biomarker](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8538839/)

## Abstract
Exposure in utero to particulate matter (PM2.5 and PM10) is associated with maladaptive health outcomes. Although exposure to prenatal PM2.5 and PM10 has cord blood DNA methylation signatures at birth, signature persistence into childhood and saliva cross-tissue applicability has not been tested. In the Fragile Families and Child Wellbeing Study, a United States 20-city birth cohort, average residential PM2.5 and PM10 during the three months prior to birth was estimated using air quality monitors with inverse distance weighting. Saliva DNA methylation at ages 9 (n = 749) and 15 (n = 793) was measured using the Illumina HumanMethylation 450 k BeadArray. Cumulative DNA methylation scores for particulate matter were estimated by weighting participant DNA methylation at each site by independent meta-analysis effect estimates and standardizing the sums. Using a mixed-effects regression analysis, we tested the associations between cumulative DNA methylation scores at ages 9 and 15 and PM exposure during pregnancy, adjusted for child sex, age, race/ethnicity, maternal income-to-needs ratio, nonmartial birth status, and saliva cell-type proportions. Our study sample was 50.5% male, 56.3% non-Hispanic Black, and 19.8% Hispanic, with a median income-to-needs ratio of 1.4. Mean exposure levels for PM2.5 were 27.9 μg/m3/day (standard deviation: 7.0; 23.7% of observations exceeded safety standards) and for PM10 were 15.0 μg/m3/day (standard deviation: 3.1). An interquartile range increase in PM2.5 exposure (10.73 μg/m3/day) was associated with a −0.0287 standard deviation lower cumulative DNA methylation score for PM2.5 (95% CI: −0.0732, 0.0158, p = 0.20) across all participants. An interquartile range increase in PM10 exposure (3.20 μg/m3/day) was associated with a −0.1472 standard deviation lower cumulative DNA methylation score for PM10 (95% CI: −0.3038, 0.0095, p = 0.06) across all participants. The PM10 findings were driven by the age 15 subset where an interquartile range increase in PM10 exposure was associated with a −0.024 standard deviation lower cumulative DNA methylation score for PM10 (95% CI: −0.043, −0.005, p = 0.012). Findings were robust to adjustment for PM exposure at ages 1 and 3. In utero PM10-associated DNA methylation differences were identified at age 15 in saliva. Benchmarking the timing and cell-type generalizability is critical for epigenetic exposure biomarker assessment.

## Funding
The research reported was supported by the Eunice Kennedy Shriver National Institute of Child Health and Human Development (NICHD) of the National Institutes of Health, under award numbers R01HD36916, R01HD39135, R01HD40421, R01 HD076592, and R01 MH103761, as well as by a consortium of private foundations. Analyses were supported by R01 MD011716 (PI: Mitchell), R01 AG067592 (MPI: Bakulski, Ware), R01 ES025531 (PI: Fallin), and R01 ES025574 (PI: Schmidt). The content is solely the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health.

## Script Files
*Code* folder contains the script files:

  FFCW_Airpoll_DNAm_Biv_Reg.Rmd: Producing reproducible descriptive plots, bivariate descriptive statistics tables, multivariable regression
  
  FFCW_Airpoll_DNAm_DataQC.Rmd: QC the FFCW DNAm + covariates dataset & the FFCW pollution dataset. Merge the two datasets & produce variables for descriptives tables
  
  FFCW_Airpoll_DNAm_Incl_Excl.Rmd: Producing reproducible inclusion/exclusion descriptive statistics tables, flowcharts


  
  
