# Using False Colour Imagery to Depict Burn Scares from the 2025 Palisades and Eaton Fires in Los Angeles County, California
Repository for EDS 220: Working with Environmental Datasets Homework 4

**Author: [Roshan Andres Nair](https://github.com/roshananair)**

**[GitHub Repository](https://github.com/roshananair/eds220-hwk4)**

**About**

This repository contains code to produce true and false colour images overlayed with perimeters of the Eaton and Palisades fires that occured in Los Angeles County, California in January of 2025. These maps are itended to demonstrate the application of false colour imagery in portraying landcover types, particularily in burned areas after a fire

**Repository Structure**

 - EDS220-HWK4/
     - .gitignore
     - hwk4-task2-false-color-NAIR.ipynb
     - README.md

**Data**

1) Fire perimeter data is sourced from the California Department of Forestry and Fire Protection (CALFIRE) Fire and Resource Assessment Program (FRAP), which maintains and distributes this historical fire perimeter dataset for California. The specific subset of the data used in this instance is the Recent Large Fire Perimeters (GT 5000 acres), which contains information about and geometries for wildfires from 2021-2025 of 5000 acres or larger. Data was downloaded from the CALFIRE Open Data Portal hosted by ESRI's ArcGIS. 

2) Landsat data was retrieved from the Microsoft Planetary Computer data catalogue and then clipped to an area surrounding the Los Angeles fires. This landsat dataset is Landsat Collection 2 Level-2, which contains atmospherically corrected surface reflectance and surfance temperature image data collected by the Landsat 8 satellite, of which a simplified collection of red, green, blue, SWIR, and NIR bands are used.

**References**

1. California Department of Forestry and Fire Protection (CAL FIRE), Fire and Resource Assessment Program (FRAP). (2026). Recent Large Fire Perimeters (GT 5000 acres) [Sublayer 1], in California Historical Fire Perimeters (Version Firep25_1) [Data set]. ArcGIS Online. https://www.arcgis.com/home/item.html?id=c3c10388e3b24cec8a954ba10458039d&sublayer=1

2. Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [Data set]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6