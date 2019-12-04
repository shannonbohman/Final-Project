Run in binder: https://mybinder.org/v2/gh/shannonbohman/Final-Project/master

# Project objective:
A spatial and temporal analysis of sea surface height, sea surface temperature, and mixed layer depth in the Bay of Bengal (BoB)

# Data: 
I used the Global ARMOR3D L4 Reprocessed dataset from the European Union's Copernicus program. It consists of 3D Temperature, Salinity, Heights and Geostrophic Currents, available on a 1/4 degree regular grid and on 33 depth levels from the surface down to the bottom
http://marine.copernicus.eu/services-portfolio/access-to-products/?option=com_csw&view=details&product_id=MULTIOBS_GLO_PHY_REP_015_002

This project uses the weekly dataset with the following variables:
- salinity (practical salinity unit)
- temperature (degrees Celcius)
- absolute height (meters)
- geostrophic zonal velocity from thermal wind equation (meters per second)
- geostrophic meridional velocity from thermal wind equation (meters per second)
- Mixed layer depth from density threshold equivalent to a 0.2°C
decrease (meters)

# Planned analysis: 

Figure 1 shows a basemap of the area considered in this project using cartopy.

Figure 2 investigates seasonal variability in the BoB by taking temporal means of SSH and SST across the different seasons.

Figure 3 investigates the relationship between mixed layer depth and SSH.

Figure 4 investigates the propagation of SSH anomalies, ultimately finding velocity.
