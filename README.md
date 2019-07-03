# IDN_MTRA
Multihazard Transport Risk Analysis for road transport in Indonesia

Attempts to adopt the approach presented in Koks et al., 2019, specifically for an Indonesia context. Some codes and functions used are adopted and adapted from the paper's Github repository (https://github.com/ElcoK/gmtra).

In the current analysis, we calculate the assets risks of the Indonesian road network to riverine floods and earthquakes. We take into account 100-year and 1000-year flood events, as well as 250-year and 2475-year flood events. We then calculate the 'road assets vulnerability' of a province as a ratio between the total road assets risks in a province with the province's regional income. The vulnerability metrics can be used to support the Central Government's budget allocation, for instance, for hazard-proofing the roads. 

- 01_data_preprocess.ipynb provides scripts needed to process raw data from OpenStreetMap and Risk Data Platform (https://risk.preventionweb.net/)
- 02_risks_calculation.ipynb provides scripts for superimposing natural hazard maps with the road network.
- 03_vulnerability_classification.ipynb provides scripts for (i) aggregating road assets risks at a provincial level, (ii) classifying provinces based on their vulnerability (1 is the most vulnerable category while 4 is the least vulnerable category). 


Corresponding data for the Indonesia context to run the scripts can be made available upon contact with the author (bramkaarga@gmail.com).





=====References

Koks, E. E., Rozenberg, J., Zorn, C., Tariverdi, M., Vousdoukas, M., Fraser, S. A., . . . Hallegatte, S. (2019). A global multi-hazard risk analysis of road and railway infrastructure assets. Nature Communications, 10(1), 2677. doi:10.1038/s41467-019-10442-3. 
