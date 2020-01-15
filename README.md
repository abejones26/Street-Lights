# Project 1 - Street Light Outages and Crime Analysis

## Description
Present data of 311 reports on street light outages in Chicago and find trends by neighborhood - average fix time, crime in the area, and frequent outage reports to the same address.

## Authors
* Tanisha Blakely
* Alap Raval
* Dharti Patel
* Abraham Jones


## Question(s)
a) Which Chicago neighborhoods have the most street light outages reported? 
b) What address has the most street light outage reports? Which year had the most street light outage reports?
c) Average time it takes for outages to get fixed per neighborhood?
d) What are the crime rates/reports in neighborhoods with street light outages?

## Data Set Resources

### 311 Service Requests - Street Lights - All Out - No Duplicates 
https://data.cityofchicago.org/Service-Requests/311-Service-Requests-Street-Lights-All-Out-No-Dupl/756k-itxx

### Crimes - 2001 to present 
https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2

### Boundaries - Community Areas (current)
https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6

### Population Data by Community Area:
http://www.actforchildren.org/wp-content/uploads/2018/01/Census-Data-by-Chicago-Community-Area-2017.pdf

## Installation

Use the package managers [conda](https://docs.conda.io/en/latest/) and [pip](https://pip.pypa.io/en/stable/) to install following dependencies.

```bash
conda install -c conda-forge descartes
conda install geopandas
pip install shapely
```