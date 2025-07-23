# Regional ecosystem model name
OSMOSE-NS

## Contacts
Alaia Morell (alaia.morell@gmail.com, alaiam@uw.edu)
Emy Cottrant (emycottrant@gmail.com)

## Spatial scale forcing
Regional, 0.25°x0.5°. Outputs were rescaled to 0.25°x0.25° for submission to FishMIP.

## Levels of gear disaggregation
Size selective fishing mortality by species 

## Levels of functional group disaggregation
The model has 16 focal species (4 pelagic and 12 demersal) and is forced by 10 prey groups (2 phytoplankton groups, 3 zooplanton groups and 5 benthic groups). 
Species in pelagic group: Herring, mackerel, sprat and horse mackerel.
Species grouped together in the demersal group: Sandeel, Norway pout, plaice, sole, saithe, cod, haddock, whiting, dab, grey gurnard, hake and shrimp. Sandeel and shrimp have both pelagic and demersal behavior: their biomasses have been attributed to demersal behavior because it is their primary behavior.

## Spatial grid-cell allocation method
The model applies a uniform fishing mortality rate across space.

## Fishing mortality rate equation
Time-varying fishing mortality is applied by species and size class. Size-based selectivity is informed by regional stock assessments, while total fishing mortality is scaled during calibration to reproduce observed catch data.

## Selectivity (size, age, species)
Fishing mortality is described with a vector of fishing mortality by size (0.5 or 1 cm resolution) per species.

## Model calibration
The model is calibrated using maximum likelihood estimation based on an optimization method which is an evolutionary algorithm available in the package calibraR in R (Oliveros-Ramos and Shin, 2016). 
The likelihood is initially obtained by comparing model outputs to observed data: landings (ICES, 2019a), size-at-age from scientific surveys (NS-IBTS-Q1, ICES. North Sea International Bottom Trawl Survey (2010-2019) and estimated biomasses for assessed species (ICES, 2016, 2018a, 2018b, 2018c, 2019b). The discard rate of assessed species is low except for dab and plaice: the data used as landings and biomass for these species includes estimated discards from stock assessments. The biomasses estimated for stocks entirely located within the study area are directly used (herring, sandeel, sprat, sole, and whiting). For stock with a wider distribution than the study area, the biomass data is taken proportional to total stock biomass according to the ratio between landings in the study area and total landings (mackerel, norway pout, plaice, saithe, cod, haddock, dab, hake). There is no biomass target value for unassessed species (horse mackerel, grey gurnard, hake, shrimp). The calibration is performed for an average state of the ecosystem for the period 2010-2019 by using observed data averaged over the period as target values. The calibrated parameters are: (1) the LTL group accessibility coefficients, (2) the larval mortalities, (3) the maximum ingestion rates, (4) the maximum fishing mortality rates and (5) the additional mortality rates are added in the last phase.

## Catchability and creep (yearly rate of change catchability) estimates
NA

## Further details on calibration 
Target data were updated to cover the period 1963-2010 using biomass predicted by stock assessment (Herring, Mackerel, Sandeel, Sprat, Norway pout, Plaice, Sole, Saithe, Cod, Haddock, and Whiting). 
Catch data are informed by ICES database.  More details on calibration process and data are provided in Morell et al. 2023. 

## Statistical metrics
We used negative log likelihood. 

## Statistical results (summary)
NA

## Model changes or improvements made as a result of calibration
NA

# Additional details 
NA

## Downscaling method
Global fishing effort was used except for whiting and grey gurnard where the local effort and global effort correlation was lower than 0.5. 

## “Base year" range of the regional model
Base year was year 2010. Relative effort was calculated relative to this year. 

## Environmental and biogeochemical variables and equations
Forcing variables are phytoplankton, zooplankton, temperature and oxygen. Oxygen and temperature varies according to the species position in the water column (pelagic, demersal, benthic). 

## References 

Morell, A., Shin, Y.-J., Barrier, N., Travers-Trolet, M., Halouani, G., Ernande, B., 2023. Bioen-OSMOSE: A bioenergetic marine ecosystem model with physiological response to temperature and oxygen. Progress in Oceanography 216, 103064. https://doi.org/10.1016/j.pocean.2023.103064
