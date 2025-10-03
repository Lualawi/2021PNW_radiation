# The Role of Near Solstice Solar Radiation on the Pacific Northwest Heatwave of 2021
## Contents
This repository contains the code to recreate the results of Ndoping et al (2025) as well as the supplementary materials.

Note: The published paper names scenarios Rad+30 and Rad+60 to denote the time from the CTRL simulation. For ease these notebooks use `july` (or `jul`) for Rad+30 and `aug` for Rad+60. 
### Notebooks
#### (1) figures_for_paper.ipynb: 
  Contains code to recreate the figures from the paper (see figures section of README). Needs both WRF and ERA5 (2-m) data.
#### (2) data_for_paper.ipynb
  Contains code to recreate the results of the study. Needs both WRF and ERA5 data. Contains functions to calculate the mean temperature and incoming radiation over the heatwave region, as well as the max temperature over the region. 
#### (3)supplementary_code_plots.ipynb
  Contains the code to produce the results and plots from the supplementary materials. Needs WRF and ERA5 data.

## Figures
**Figure 1:** Model Validation
![image](https://github.com/Lualawi/2021PNW_radiation/blob/main/figure1.png)
![image](https://github.com/user-attachments/assets/b6132bca-27f2-4c7a-a811-88fd193dd286)
**Figure 2:** 2-m Temperature and Radiation
![image](https://github.com/Lualawi/2021PNW_radiation/blob/main/figure2.png)
**Figure 3:** 2-m Max T Differences and Record Exceedances for Main Simulations
![image](https://github.com/Lualawi/2021PNW_radiation/blob/main/figure3.png)
**Figure 4:** 2-m Max T Differences and Record Exceedances for Sensitivity Studies
![image](https://github.com/Lualawi/2021PNW_radiation/blob/main/figure4.png)

## Abstract of Study
In late June 2021, the Pacific Northwest in Canada and the U.S. experienced a severe heatwave, shattering temperature records and making worldwide news. The extreme temperatures have been attributed to an anomalously strong atmospheric block, high moisture content of upstream air, and dry soils. We present the first study quantifying the impact of the near-maximum incoming solar radiation resulting from the event's proximity to the summer solstice. Using the Weather Research and Forecasting model, we contrast the observed heatwave with meteorologically identical heatwaves, but with incoming solar radiation of 30 (+30d) and 60 days (+60d) later. Spatially averaged mean heatwave temperatures are reduced by 1.5 degree C (4.8 degree C) in +30d (+60d), and the spatial area over which records were broken is reduced by 25% (81%). Although our results suggest that the heatwave would still have broken 80-year records even in our +60d simulation, heatwave timing likely played a significant role in the maximum heatwave temperatures.
