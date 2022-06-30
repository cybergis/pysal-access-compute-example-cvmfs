# Pysal Access Compute Example

**Authors:** Alexander Michels, Taylor Ziegler, Zimo Xiao, and Mit Kotak

![Map of Chicago showing travel-cost](img/Chicago.png)

This is an example job for the [CyberGIS-Compute](https://cybergis.github.io/cybergis-compute-python-sdk/index.html) job service using [Pysal's Access package](https://pysal.org/access/index.html) and their example datasets to calculate spatial accessibility. The notebook walks through: (1) exploring the data from Pysal with Geopandas, (2) the basics of a CyberGIS-Compute model and how this model was implemented for CyberGIS-Compute, (3) running the accessibility analysis on a High Performance Computing (HPC) resource with CyberGIS-Compute, (4) getting the results back from the HPC resource and (5) doing some simple analysis and plotting with the results.