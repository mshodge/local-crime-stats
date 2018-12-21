# local-crime-stats
Some jupyter notebook codes for analysing local crime stats in Llandaff North and Gabalfa, Cardiff

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
