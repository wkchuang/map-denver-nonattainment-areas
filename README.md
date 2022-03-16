# Mapping the Denver Nonattainment Area
Creates maps for different nonattainment areas in the Denver region

The EPA changed the boundary of the Denver nonattainment area for the 2015 National Ambient Air Quality Standard (NAAQS) while keeping the boundary for the 2008 NAAQS the same. This created two boundaries for two standards and necessitated a description in the State Implementation Plan (SIP). This code creates a figure for the SIP and other public communication efforts.

We use `geopandas` to handle the shapefiles, `shapely` to combine polygons together, and `folium` to draw the maps. Because folium maps do not currently (2022-03-15) render correctly within a jupyter notebook, one workaround is to put the link to the notebook into http://nbviewer.org/
