**Model name**

*Atlantis southern Benguela*

**Contacts**

*Kelly Ortega (kelly.ortegacisneros\@uct.ac.za)*

**Spatial scale forcing**

$$For example: scale: global or region, resolution: ¼ and 1 degree model runs$$

*region, ¼ and 1 degree model runs*

**Levels of gear disaggregation**

$$Which gears are used in the model, how was the effort aggregated or disaggregated?$$

*Purse-seine fisheries, inshore and offshore demersal trawl fisheries, mid-water trawl fishery, jig fishery, linefisheries. The model uses fishing mortality and not effort to model fisheries, fishing mortality at the species and species group level were available from the South African Department of Fisheries.*

**Levels of functional group disaggregation**

$$Which functional groups are used in the model, how was effort allocated across groups?$$

*The second version of the model has 32 functional groups: 19 age-structured populations, 9 biomass pools, 2 detrital groups and 2 bacterial groups. Target and bycatch species are subject to different levels of fishing mortality.*

**Spatial grid-cell allocation method**

$$How was fishing effort allocated across grid-cells? Please provide equations as well as description$$

*The current version of the model applies the same fishing mortality rate across space and uses age selectivity as the minimun age at which fishing mortality applies.*

**Fishing mortality rate equation**

$$How are fishing mortality and catch rates calculated in your model? Please provide equations as well as description$$

![](images/atlantissouthernbenguela.png){fig-align="center"}

*The southern Benguela Atlantis uses "a fisheries induced mortality rate, defining a proportion of biomass to be harvested per day" option 2 in secion 15.1. Atlantis manual part II (version July 2022).*

*mFC is the fishing mortality rate, Biom~CX~ is the biomass of a group i in a box j, sel~Y,i~ is the selectivity of fishery Y on group i, managesc~Y~ is the TAC management scalar, mpasc~Y,j~ optional MPA scalar applied to fishery Y in a box j and brok~Y~ is the broken stick management scalar for the fishery Y.*

*Source: Atlantis manual part II (version July 2022).*

**Selectivity (size,age,species)**

$$If you have a selectivity term please describe it, with equation$$

*The southern Benguela uses simple age selectivity, which is "the minimun age of a species at which fishing mortality applies". It uses the XXX_mFC_startage parameter, same fishing mortality is applied to all groups over the minimum age.*

**Model calibration**

$$Catchability terms can be used to calibrate the model to catches, using data ONLY UP TO 2004. Please state how you estimate these parameters and the metrics and criteria you use to calibrate your model. Please provide details and equations$$

*Biomass and catch time series from 1990-2013 for the main fisheries targets in the southern Benguela were used to calibrate the model. Model skill was evaluated using five metrics (including correlation coefficients) to determine the skill of model outputs in representing observed time series. Details in Ortega-Cisneros et al., 2017.*

**Catchability and Creep (yearly rate of change catchability) Estimates**

$$Please provide details on the specific estimated parameters from the calibration, e.g. range of creep of 2-5% per year; and catchability coefficients per gear / functional group as necessary$$

*No catchability information has been incorporated into the model, since this information is only available for a few fleets in the southern Benguela. Creep is not incorporated in this model.*

**Further details on calibration**

$$Have you used other metrics or data in your calibration?$$

*See Ortega-Cisneros et al., 2017 for details on model skill assessment.*

**Statistical metrics**

$$Please provide detail on the statistical method used in your calibration - E.g. optimisation, error terms$$

*Model skill was evaluated using quantitative univariate metrics that compared observational data (total biomass, catch and proportion of a species' biomass in each box) to model outputs.The data used for model skill evaluation in this study consisted of biomass time-series of anchovy, cephalopods (chokka squid, Loligo reynaudii), horse mackerel, sardine, shallow- and deep-water hake, round herring and snoek from 1990 to 2013.*

*In accordance with the recommendations of Stow et al. (2003, 2009), a number of different indices of model performance were used that collectively provide a comprehensive skill assessment. The biomass data were standardized and the average error (AE), average absolute error (AAE), root mean squared error (RMSE), modelling efficiency (MEF) and correlation coefficients (Kendall, Pearson and Spearman) were calculated. Source: Ortega-Cisneros et al., 2017*

**Statistical results (summary)**

$$Please provide a summary of the metrics and results associated with your model calibration - E.g. RMSE with observed catches and any other process-based or theoretical criteria used to calibrate the model, comparison of modelled biomass, growth rates, P\"B ratios etc$$

*The ABACuS v2 model had the highest skill for sardine biomass and the poorest for horse mackerel biomass across all skill metrics. Spearman correlation coefficients showed positive correlation for all analysed groups (sardine, anchovy, round herring, shallow- and deep-water hake, snoek and cephalopods), with the exception of horse mackerel. Clear correlations (\> 0.5) were found for anchovy, sardine, round herring and both hake species. The average error values were very low (\< 0.0001) for most groups, with the exception of horse mackerel, snoek and cephalopods. Sardine, round herring and both hake species had the lowest average absolute errors and root mean square errors among groups. These species also had positive modelling efficiency (MEF) values, indicating that the modelled biomass of these groups performed better than using the average of observations. Anchovy biomass performed slightly worse than the 0 threshold with a MEF of −0.03. Modelled biomasses for snoek and cephalopods ranked among the lowestfor MEF, and horse mackerel had the lowest value. Source: Ortega-Cisneros et al., 2017*

**Model changes or improvements(s) made as a result of calibration**

$$Please provide detail of any other parameters or model changes since the last round as a result of this calibration$$

NA

**ADDITIONAL DETAILS FOR REGIONAL MODELS ONLY:**

**Downscaling method**

$$Please describe further details how the LME level fishing effort was downscaled to your region, providing further information on what data, if any were used, E.g. $$

*I have not yet analized the fishing effort data*

**The "base" year range of the regional model**

$$If you expressed effort relative to the effort in your base model, which year was the base year and how was this done$$

*1990 was used as the base year.*

**References**

Audzijonyte, A., Gorton, R., Kaplan, I., Fulton, E. 2017. Atlantis User's Guide Part II: Socio-Economics. Current update: July 2022.

Ortega-Cisneros, K., Cochrane, K., Fulton, K. 2017. An Atlantis model of the southern Benguela upwelling system: Validation, sensitivity analysis and insights into ecosystem functioning. Ecological modelling 355:49-63. 10.1016/j.ecolmodel.2017.04.009
