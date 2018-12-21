# local-crime-stats
Some jupyter notebook codes for analysing local crime stats in Llandaff North and Gabalfa, Cardiff

## Findings So Far

*A major limitation was that the crime data only went back to January 2016, so historical trends cannot be inferred.*

### All crimes

- Since JAN-2016 there have been 4,661 crimes committed in Llandaff North and Gabalfa (LN&G).
- Since JAN-2016 the number of crimes in LN&G has remained on average around 165 per month. 
- The month with the fewest number of crimes was FEB-2018 (117) and the month with the greatest, MAY-2016 (207). 
- In 2018, the month with the greatest number was OCT-2018 (197). The month with the fewest was FEB-2018 (117).
- 2018 so far has the fewest number of crimes (1,559), even using the average for DEC (156), this is still fewer than 2016 (1,827) and 2017 (1,876).
- The first half (JAN-JUN) of 2018 has fewer crimes (686) than 2016 (775) and 2017 (862).
- The second half of 2018 (currently 873 crimes) looks set to surpass 2016 (892) and 2017 (871); with the DEC average (156), this is set to be 1,029 crimes.

### Crime Type Breakdown

- The most occurring crime was violent crime (1084), followed by vehicle crime (907).
- The least occurring crime was theft from person (22), robbery (22) and possession of weapons (33).

### Action/Response

- The action for the majority of crimes was *Investigation complete; no suspect identified* (2,482). The second most common action was *Unable to prosecute suspect* (1,123).
- Particular crimes had frequent outcomes. For, bicycle thefts (262) the majority of crimes resulted in *Investigation complete; no suspect identified* (228), but 15 crimes did result in *Suspect charged as part of another case*. 
- The crime that sent the most offenders to prison was shoplifting (53), followed by violent crime (42).


## To Do List
- [x] Get crime stats API call working
- [x] Setup Jupyter Notebooks
- [x] Plot time-series of crime
- [x] Plot action response to crime
- [ ] Analyse time-series for seasonal trends
- [ ] Analyse hotspots using geospatial tools

## Data Source

Crime data was sourced using API calls to [https://data.police.uk/docs/](https://data.police.uk/docs/).
Area polygons were sourced from MapIt [Gabalfa](https://mapit.mysociety.org/area/12047.html) and [Llandaff North](https://mapit.mysociety.org/area/12046.html). These were simplified because crime API doesn't handle complex polygons.
