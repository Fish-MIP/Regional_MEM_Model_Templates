# Regional ecosystem model name
DynaMICE California Current

## Contacts
Stefan Koenigstein, Leibniz Centre for Tropical Marine Research: stefan.koenigstein@leibniz-zmt.de

## Spatial scale forcing
24 spatial cells, ca. 2° lat by 75-150km dtc

## Levels of gear disaggregation
Coastal pelagic purse seine fleet only

## Levels of functional group disaggregation
Coastal pelagic fish species (Pacific sardine, Northern anchovy) only, effort calculated from annual landings and biomass data per age class.

## Spatial grid-cell allocation method
Selectivity calibrated based on annual spatial distribution and landings per age class data for two fleets:
1. Pacific Northwest
2. Californian-Mexican

## Fishing mortality rate equation
Calibrated based on annual landings and biomass data per age class from long-term stock assessment models (NOAA SWFSC).

## Selectivity (size, age, species)
Age-, species- and fleet-dependent catchability 

## Model calibration
Original ensemble model configuration based on regional ocean-bgc model output, and global sensitivity analysis and calibration to annual at-age biomass and landings data 1980–2022, as described in Koenigstein et al. 2022. 
Not re-calibrated for FishMIP, but selected viable (stable) ensemble members using FishMIP forcings, and ensemble mean provided. 

## Catchability and creep (yearly rate of change catchability) estimates
N/A 

## Further details on calibration 
California sea lion diet time series and 'Rockfish Recruitment and Ecosystem Assessment Survey' data; Koenigstein et al. in prep. 

## Statistical metrics
RMSE, Pearson's R 

## Statistical results (summary)
Original calibration:  
Pacific sardine: Total adult biomass (1980-2018) pseudo-R2 = 0.62–0.83 over ensemble.  
Northern anchovy: Pearson's R to RREAS survey index (1980–2022) = 0.58–0.72 over ensemble, sea lion consumption of anchovy (1980–2022): Pearson's R 0.38–0.59 over ensemble.  

## Model changes or improvements made as a result of calibration
N/A

# Additional details 
The sections below are designed to better capture additional steps needed to run ecosystem models at a regional scale.

## Downscaling method
N/A

## “Base year" range of the regional model
1980–2022 (annual)

## Environmental and biogeochemical variables and equations
Sea surface temperature, Seawater potential temperature averaged over 10–32.5m, dissolved oxygen averaged over 10–32.5m, seawater X velocity (offshore transport), carbon content of picophytoplankton, diatoms, micro- and mesozooplankton. Bias-corrected with regard to equivalent variables from original forcing, described in Koenigstein et al. 2022 & in prep.

