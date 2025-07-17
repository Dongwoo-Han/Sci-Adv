# Sci-Adv
This repository contains the data used for figures regarding the manuscript titled as '*Post-subduction bending-induced faults and hydrothermal circulation provide misleading estimates of friction in subduction zones*'.

The content of each file can be identified by the file name, as described below.  

**SubductionZone_ModelConditions_DataType** (e.g., Nankai_MuPrime0.00_Ka1E-10m2_xsw-10km_CalculatedSeafloorHeatFlow)  
- SubductionZone is either Nankai or Tohoku  
- ModelConditions is either non-HC_Model, BestFitModels, or MuPrimeXXX_KaYYYm2_xswZZZkm.  
XXX, YYY, and ZZZ are the values used for each parameter in the models.  
Please note that MuPrimeXXX is not included in the file names of the permeability data.

Each file has either two (x-coordinate (km) and data) or three (x- and y- coordinates (km), and data) columns.

DataType
01. PercentageImprovement: percentage improvement of the calculated seafloor heat flow of the best-fit models compared to those calculated from the non-HC models (%)
02. CalculatedSeafloorHeatFlow: calculated seafloor heat flow averaged every 5 km (mW m-2)
03. Temperature: temperature distribution (Kelvin)
04. Vx: pore fluid velocity in x-direction (m s-1)
05. Vy: pore fluid velocity in y-direction (m s-1)
06. PermeabilityProfile: log10(permeability) (m-2)
