# Analysis of the Australian Bushfires (2019 - 2020)
This reposirtory conducts an analysis of the 2019 - 2020 Australia Wildfire impacts. The bush fires are estimated to have burned about 24.3 million hectares (60 million acres), impacting the local fauna and flora. Our analysis will further dive into the impacts of the wildfire on the landcover and evapotranspiration of Australia. 

To access the data for the analysis it can be aquired via <a href = "https://earthengine.google.com" >Google Earth Engine </a>.

### Authors
Dalila Lara, UC Santa Barbara (dalilalara@ucsb.edu)
Ruth Enriquez, UC Santa Barbara (rbe786@ucsb.edu) 
Michael Zargari, UC Santa Barbara (mzargari@ucsb.edu)

### Content
- final_project_team9.ipynb: Jupyter notebook containing analysis and walkthrough of the GEE data
- environment.yml: Template environment file for use in creating Binder environment for running Jupyter notebook

### Data
<a href="https://developers.google.com/earth-engine/datasets/catalog/ESA_CCI_FireCCI_5_1#dois" >MODIS Fire_cci Burned Area Pixel Product, Version 5.1 </a>

<a href = "https://developers.google.com/earth-engine/datasets/catalog/TERN_AET_CMRSET_LANDSAT_V2_2"> Actual Evapotranspiration for Australia (CMRSET Landsat V2.2) </a>

The data we are using can be accessed by Google Earth Engine. To use GEE one must have an account, be sure to authenticate and initialize GEE in order to run the notebook successfuly. 

### Packages 
The packages we will be using include ee, geemap, pandas, matplotlib, numpy, & cartopy. These packages will allow us to read in the GEE data, maniuplate the data, and map the data. 


[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/EDS220-Fall2022-org/homework-2-team9.git/main?labpath=final_project_team9.ipynb)