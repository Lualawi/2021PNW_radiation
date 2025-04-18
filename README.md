# The Role of Near Solstice Solar Radiation on the Pacific Northwest Heatwave of 2021
## Contents
This repository contains the code to recreate the results of Ndoping et al (2025) as well as the supplementary materials.

Note: The published paper names scenarios Rad+30 and Rad+60 to denote the time from the CTRL simulation. For ease these notebooks use `july` (or `jul`) for Rad+30 and `aug` for Rad+60. 
### Notebooks
#### (1) plots_for_paper.ipynb: 
  Contains code to recreate the figures from the paper (see figures section of README). Needs both WRF and ERA5 (2-m) data.
#### (2) data_for_paper.ipynb
  Contains code to recreate the results of the study. Needs both WRF and ERA5 data. Contains functions to calculate the mean temperature and incoming radiation over the heatwave region, as well as the max temperature over the region. 
#### (3) supplementary_code_plots.ipynb
  Contains the code to produce the results and plots from the supplementary materials. Needs WRF and ERA5 data.

## Figures
**Figure 1:** Model Validation
![image](https://github.com/user-attachments/assets/b6132bca-27f2-4c7a-a811-88fd193dd286)
**Figure 2:** 2-m Temperature and Radiation
![image](https://github.com/user-attachments/assets/2ddd33e6-3c3e-4d54-815a-1135e1e43606)
**Figure 3:** 2-m Max T Differences and Record Exceedances for Main Simulations
![image](https://github.com/user-attachments/assets/3239b48c-2cce-4055-80d7-9a272d24e1fe)
**Figure 4:** 2-m Max T Differences and Record Exceedances for Sensitivity Studies
![image](https://github.com/user-attachments/assets/23d11e4e-e157-4e30-8001-4ba582fd3c90)

## Abstract of Study
In late June 2021, the Pacific Northwest experienced a severe heatwave, shattering temperature records and making worldwide news. The extreme temperatures have been attributed to an anomalously strong atmospheric block, high moisture content of upstream air, and dry soils. We present the first study quantifying the impact of the near-maximum incoming solar radiation resulting from the event's proximity to summer solstice. Using the Weather Research and Forecasting model, we contrast the observed heatwave with meteorologically identical heatwaves, but with incoming solar radiation of 30 (Rad+30) and 60 days (Rad+60) later. Spatially averaged maximum heatwave temperatures are reduced by 4.8 degrees C (1.5 degrees C) in Rad+30 (Rad+60), and the spatial area over which records were broken is reduced by 25% (80%). Although our results suggest that the heatwave would likely have broken all-time records even in our Rad+60 simulation, we have demonstrated that the timing of heatwaves likely plays a significant role in the maximum temperatures that will occur.

%In ERA5 observationally-based data the heatwave broke 80-year records over 1,793,000 km^2 across the PNW; while the model ran at Rad+60 day radiation conditions shows that local temperature records would be broken only over 499,000 km^2 (a reduction of 72%) with both maximum and average temperatures in the region ~4 \degree C lower than the real event. Sensitivity tests show that our results are robust to changing the land-surface model and radiation parameterizations. We find that the 2021 PNW Heatwave was influenced by the increased solar radiation; however, even under late August solar radiation conditions local temperature records would likely still have been broken.
