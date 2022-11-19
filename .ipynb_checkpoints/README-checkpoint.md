## Moderate Resolution Imaging Spectroradiometer (MODIS) Burned Area 
This repository contains useful information to access and analyze the Moderate Resolution Imaging Spectroradiometer (MODIS) Burned Area data on Google Earth Engine (GEE).

### Authors
Dalila Lara, UC Santa Barbara (dalilalara@ucsb.edu)
Ruth Enriquez, UC Santa Barbara (rbe786@ucsb.edu) 
Michael Zargari, UC Santa Barbara (mzargari@ucsb.edu)

### Content
- final_project_team9.ipynb: Jupyter notebook containing analysis and walkthrough of the GEE data
- environment.yml: Template environment file for use in creating Binder environment for running Jupyter notebook

### Data
<a href="https://developers.google.com/earth-engine/datasets/catalog/ESA_CCI_FireCCI_5_1#dois" >MODIS Fire_cci Burned Area Pixel Product, Version 5.1 </a>

The data we are using can be accessed by Google Earth Engine. To use GEE one must have an account, be sure to authenticate and initialize GEE in order to run the notebook successfuly. 

### Packages 
The packages we will be using include ee, geemap, pandas, matplotlib, numpy, & cartopy. These packages will allow us to read in the GEE data, maniuplate the data, and map the data. 