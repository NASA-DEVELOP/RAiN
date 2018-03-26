===============
 Rainfall Analysis INtegration (RAIn)
===============

Date Created: July, 27, 2017

This Google Earth Engine (GEE) tool is an exploratory tool that allows the user to view spatial information related to precipitation and resiliency. Most of the data sets are global or near global, but they are clipped to the country of Niger for Mercy Corps’ efforts there.

 Required Packages
===================
* Google Earth Engine Code Editor
* Logged in as DEVELOP.mercycorps@gmail.com
* This code is written in JavaScript for GEE

 Parameters
---------------
1. Log into code.earthengine.google.com
2. Select the RAIn_Full code
3. Press Start at the top of the page
4. The user interface is along the left of the map output with selections of layers to be explored. When selected, the map is cleared and the corresponding layer is shown. 
5. Multiple layers can be explored by checking the corresponding boxes in the Layers dropdown at the top right hand of the map. The sliders next to each layer can be used to adjust transparency.
6. Click on an area of interest on the map to view time series data for CHIRPS precipitation, Land Surface Temperature, and NDVI. These charts area can be viewed in the Console tab at the upper right on the page. 
Map Layers
----------------
Agricultural Zones: USAID. Not dynamic. Saved as asset

Commune Boundaries: UC Berkeley. Saved as asset

Human Population: WorldPop. Dynamic in GEE

Age Demographics: WorldPop. Divided into appropriate demographics for Niger. Saved as assets

Oxford – Malaria % under 5 infected: Oxford MAP Plasmodium Falciparum Malaria in Africa. Dynamic in GEE

Major Health Sites: NASA SEDAC. Saved as asset

GRACE – Groundwater Change: This is a SAMPLE LAYER of model data, provided by Bailing Li at NASA GSFC. Saved as asset

MODIS – Land Surface Temperature: Dynamic in GEE

GPM – Rainfall: Dynamic in GEE

TRMM – Rainfall: Dynamic in GEE

CHIRPS – Rainfall: Dynamic in GEE

MODIS NDVI – Vegetation Greenness: Dynamic in GEE

MODIS NDDI – Drought Index: Calculated from NDVI and NDWI in GEE. Dynamic in GEE

Contact
---------
Name(s): Jared Tomlin
E-mail(s): jt12@hood.edu

***
This file will be extended in the next few weeks as the code is finalized. Updates will include better visualization, a date picker and tool tips for each layer that will include longer descriptions of the data sources. Detailed information about sources, use, resolution, and DOIs for the data are documented in the tech paper. 

