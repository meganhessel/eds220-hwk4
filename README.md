# eds220-hwk4
## False Color Imagery of Eaton and Palisades Fires
*Author: Megan Hessel*
*Date: December 8, 2025*

### About 

In this project, we use satellite data to create true and false color imagery to inspect the burn damages of 2025 Palisades and Eaton wildfires in Los Angeles. In order to accomplish this, I used remote sensing data, check and manipulate coordinate reference systems, and explored various color band combinations to highlight the fire scars. Furthormore, we investigate the effected, uninsured populations using the Environmental Justice Index.


### Repository Structure
Located in my root repository is the main jupyter notebook, README, the gitignore, and a picture of a wildfire. 

```{python}
eds220-hwk4 
├──.DS_Store
├──.gitignore
├──fire_picture.jpg
├── hwk4-task2-false-color-HESSEL.ipynb
├── README.md
```


### Data
The data is accessible through online plateforms. 

1.  Landsat 8 satellite recorded a collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data. Data was obtained from the [Microsoft Planetary Computer data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2).

2.  Geometries of the Eaton and Palisades fire perimeters from the [County of Los Angele's ArcGIS page](https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about).

3. California's Environmental Justice Index (EJI) is a collection of the demographics, environmental burdens, and health statistics for each census track in California. The EJI data is from the [Geospatial Research, Analysis, and Service Program (GRASP)](https://www.atsdr.cdc.gov/place-health/php/eji/eji-data-download.html). 

# References 

County of Los Angeles. (January 21, 2025). *Palisades and Eaton Dissolved Fire Perimeters (2025)*. AcrGIS Online. Accessed Nov 28, 2025. https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about 

Centers for Disease Control and Prevention and Agency for Toxic Substances Disease Registry. (2024). *Environmental Justice Index*. Geospatial Research, Analysis, and Service Program (GRASP). Accessed Nov 28, 2025. https://atsdr.cdc.gov/place-health/php/eji/eji-data-download.html

Microsoft. (2025). *Landsat Collection 2 Level-2*. Microsoft Planetary Computer. Accessed Dec 2, 2025. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2#overview

Ong P., Pech C., Frasure L., Comandur S., Lee E., and González S. (n.d.). *LA Wildfires: Impacts on Altadena’s Black Community* University of California, Los Angeles Ralph J. Bunche Center. Accessed Nov 28, 2025. https://bunchecenter.uclaRJC.edu/wildfires-altadena-black-community/ 

The California Department of Forestry and Fire Protection (Cal Fire). (2025a). *Eaton Fire*. Accessed Dec 2, 2025. https://www.fire.ca.gov/incidents/2025/1/7/eaton-fire

The California Department of Forestry and Fire Protection (Cal Fire). (2025b). *Palisades Fire*. Accessed Dec 2, 2025. https://www.fire.ca.gov/incidents/2025/1/7/palisades-fire

