# PythonScripts
Scripts Written in Python to automate geophysical data processing tasks

#ERTData_AdvancedEditingofABEMOutputs#
Allows ERT geophysical data to be read in from ABEM Terrameter products (specifically, legacy Terrameter SAS4000 lund projects and data exported from the Terrameter LS in .dat or .txt formats. Optimized for the latter.). Graphically displays the data with pseudodepths and distances. Can edit out entire electrodes or based on the Percent Error of points based on other points at the same pseudodepth. Will automatically shift data to start at 0 if it does not already. Will add topography to data if imported in correct format (ID | x-Dist | elev_m | elev_ft (opt.)). Exports in general array format for inversion in Res2DInv.

