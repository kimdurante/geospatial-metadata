---
layout: default
title: Preparing Data
nav_order: 3
has_children: true
---

## Preparing Data

* All data layers should be loaded into a collection directory (folder) that can be connected to ArcGIS.

* Layers must adhere to certain requirements to function properly within SDR, SSDI, and EarthWorks.

### Checking Data Properties
* Ensure that each layer has a valid filename, spatial reference, and geographic extent before accessioning begins. Refer to the instructions for Data Wrangling if you need to change filenames, spatial references, or extents.

* [Run this script to create a csv list of filenames, SRSs, and data types for shapefiles and/or GeoTIFFs.](https://raw.githubusercontent.com/kimdurante/metadataWorkflow/master/checkData.py)

| FILENAME       | SRS   | TYPE |
| ------------- |-------------|-----------------|
|airmonitoringstations.shp|3310|Point|
|arb_california_airbasins_aligned_03.shp|3310|Polygon|
|arb_california_airdistricts_aligned_03.shp|3310| Polygon|
|arb_california_counties_aligned_03.shp|3310| Polygon|
|fed_1hr_coabdis.shp|3310| Polygon|

### Creating a List of Layers

* 

### Registering Data