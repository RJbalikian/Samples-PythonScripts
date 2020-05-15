## PythonScripts
Scripts Written in Python to automate geophysical data processing tasks

# ERTData_AdvancedEditingofABEMOutputs
Allows ERT geophysical data to be read in from ABEM Terrameter products (specifically, legacy Terrameter SAS4000 lund projects and data exported from the Terrameter LS in .dat or .txt formats. Optimized for the latter.). Graphically displays the data with pseudodepths and distances. Can edit out entire electrodes or based on the Percent Error of points based on other points at the same pseudodepth. Will automatically shift data to start at 0 if it does not already. Will add topography to data if imported in correct format (ID | x-Dist | elev_m | elev_ft (opt.)). Exports in general array format for inversion in Res2DInv. With installation of correct modules this should be portable across different devices.

# EXAMPLE_CrossSectionPlot
Creates cross sections from .csv data with depths to various layers. Each layer also has an attribute. In the case of the original data, it represents thickness of coarse material within a discrete interval (i.e., 25 ft layers x 1km distance).

# EXAMPLE_Elevation Surfacedown-Public.ipynb
Jupyter notebook that separates well data into discrete layers that can be interpolated in GIS software.

# EXAMPLE_Well Interval Statistics-Public.ipynb
Jupyter notebook that calculates statistics from data processing for data quality assurance and control.
