# TextileStrengthDashboard
R Shiny Dashboard to import raw instron data of textiles and output Extension Vs. Load and select the parameters to get Tenacity vs. Strain


Raw Instron Data from Cornell- separate and extract important variables for calculations of Load vs. Extension

There is an upload file portion that can read .csv files or .raw files 
Raw data generates Grpah 1: Extension vs. Load graph that can be downloaded
Brush event from Graph 1 creates range for calculating graph 2
After brush event - generate Graph 2: Tenacity vs Strain  that can be downloaded
Double Click event for graph two outputs where user believes the Yield is, brush event for user to output slope
After brush event - Graph 3 is generated: Tenacity vs Strain linear regression model of selected region

All grpahs can be downloaded as .png
