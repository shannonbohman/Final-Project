# Scientific question to investigate: 
How do the East Asian Monsoon and ENSO phases impact the spatial variablity of SST and SSH in the Bay of Bengal?

# Data: 
The Global ARMOR3D L4 Reprocessed dataset: It consists of 3D Temperature, Salinity, Heights and Geostrophic Currents, available on a 1/4 degree regular grid and on 33 depth levels from the surface down to the bottom.
http://marine.copernicus.eu/services-portfolio/access-to-products/?option=com_csw&view=details&product_id=MULTIOBS_GLO_PHY_REP_015_002

This project uses the weekly dataset.

To download data from this site:
- Go to http://marine.copernicus.eu/
- Click on Data
- Select data. When you try to download, you will be asked to create an account. Once you have a username and password, you can download the data.

# Planned analysis: 
Figure 1 will contain four maps to give a general understanding of the spatial distribution of SST and SSH at different phases in the El Nino Southern Oscillation and East Asian Monsoon. The first map will show SSH anomaly in the entire Bay of Bengal on January 15, 2000 (winter monsoon and La Nina). The second map will show SSH anomaly on July 15, 2000 (summer monsoon and La Nina). The third map will show the SSH anomaly from January of 2005 (winter monsoon and El Nino), and the fourth map will show the SSH anomaly from July of 2005 (summer monsoon and El Nino). I'd like to visually determine which ENSO-EAM pairing demonstrates the most clearly defined "freckled face" in the Bay of Bengal (as opposed to a spatially uniform face).

Figure 2 will explore the uniformity of SSH and SST with respect to the East Asian Monsoon. It will contain a line plot of the standard deviation of SSH at each month of 2013, a neutral ENSO year. Another line (with its own y-axis, probably) will show the standard deviation of SST throughout 2013. I will then calculate the Pearson correlation coefficient between the standard deviations of SST and SSH to see if there is any relationship between the uniformity of SST and the uniformity of SSH.

Figure 3 will explore the relationship of SST and SSH to mixed layer depth in the Bay of Bengal. I will group the data by month and then take the mean from 2000-2011 so that each month has a mean value for SST, SSH, and MLD. The first scatter plot will show SST versus MLD, the points color coded for month. The second scatter plot will show SSH versus MLD with the same color coding. For each plot I will determine the correlation coefficient and p-value.

Figure 4 will contain two Hovmoller diagrams demonstrating the propagation of anomalous SSH and SST events. The first diagram will plot SSH anomaly with longitude (from 77E-100E) on the x-axis and time (from 1999-2005) on the y-axis, and the second diagram will have the same structure, but SST anomaly will be plotted. This will provide insight into how eddies move in the Bay of Bengal.
