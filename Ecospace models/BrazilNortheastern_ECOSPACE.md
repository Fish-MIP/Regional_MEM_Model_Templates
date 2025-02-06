# Model name

Brazilian northeastern Ecospace Model

# Contacts

Alex Lira (alexliraufrpe@outlook.com), Ronaldo Angelini (ronangelini@gmail.com), Leonardo Capitani (leocapi07@gmail.com)

# Spatial scale forcing

Regional at 1.2 $km^2$ grid resolution (515 lines \* 250 columns, 17,290 grid cells, total ecosystem area modeled 31,105 $km^2$)

![image](https://github.com/user-attachments/assets/d8cb8d4c-00ac-412b-9ec0-b39214c11a16)

# Levels of gear disaggregation

4 fleets (Longline, bottom trawl, pots/traps, and seine nets)

# Levels of functional group disaggregation

55 functional groups (36 fish species or groups, ten invertebrates, three mammals, one bird, one reptile, three primary producers, and one detritus)

# Spatial grid-cell allocation method

Simple fishing effort gravity model based on cost/benefit analysis

JS to dig up formula

# Fishing mortality rate equation

*How are fishing mortality and catch rates calculated in your model? Please provide equations as well as description*

# Selectivity (size, age, species)

*If you have a selectivity term please describe it, with equation*

# Model calibration

We calibrated the Ecosim model using the "Fit to Time Series" routine, using fishing landings for 19 species (1987-2007) and primary productivity time series.

# Catchability and Creep (yearly rate of change catchability) Estimates

*Please provide details on the specific estimated parameters from the calibration, e.g. range of creep of 2-5% per year; and catchability coefficients per gear / functional group as necessary.*

# Further details on calibration

Primary productivity was used to drive temporal variability of production of the phytoplankton compartment in the model. The fit was improved by automatically changing the vulnerability values for each interaction between a predator and prey, reducing the sum of squares between predicted and observed data.

# Statistical metrics

*Please provide detail on the statistical method used in your calibration - E.g. optimisation, error terms*

N/A

# Statistical results (summary)

*Please provide a summary of the metrics and results associated with your model calibration - E.g. RMSE with observed catches and any other process-based or theoretical criteria used to calibrate the model, comparison of modelled biomass, growth rates, P\"B ratios etc.**

N/A

# Model changes or  improvements(s) made as a result of calibration

Vulnerabilities values were increased for groups Hypanus spp, Other Zoobentivores and Other Invertivores, and reduced for Caranx spp, Sharks and Other Piscivores. In general, the vulnerability matrix maintains the original values (\~2).

# ADDITIONAL DETAILS FOR REGIONAL MODELS ONLY:

## Downscaling method

We used several Brazilian official fisheries reports (e.g., IBAMA, 2007; IBGE, 1989) to reconstruct the historical fisheries catches in the area for the period 1987-2007. In addition, we used relative effort (kW x 1000) by fishing gear (longline, bottom trawl, pots/ traps, and seine nets) from the Sea Around Us (SAU) project for Brazil (Pauly and Zeller, 2015).

Although the categorization of fishing gears is commonly used to denote commercial fishing in the area, we adopted the same categorization for small-scale fisheries because they are common in capturing exploited species (Diegues, 2006).

**The \"base\" year range of the regional model**

1987-2007
