# Compiling Data for Mineral Prospectivity Modeling

## Study Area
* Natural boundaries (i.e. geologic domains) over arbitrary boundaries
* Ideally collect data within the study area + a buffer to help minimize edge effects
* Early on decide on an appropriate projection
* Prefer meters over feet, not decimal degrees

## Reference Points (Deposits)
* Single points for regional scale, potentially orebody outlines for district scale
* Include endowment for commodities being modeled
  * Deposits are not equal, supports "weighted" modeling
* Include deposit type and/or other classifiers when reference points are not part of the same population
  * Supports separate models by class
* Other data of potential interest
  * Grade
  * Age of mineralization

## Data
* Use widely adopted "standard" formats whenever possible
  * Shapefiles for vector data
  * GeoTiffs for raster data / grids
* GDAL is a good source for supported formats
  * [Vector](https://gdal.org/en/stable/drivers/vector/index.html)
  * [Raster](https://gdal.org/en/stable/drivers/raster/index.html)
* Prefer formats that promote consistency (i.e. databases) over spreadsheets
* Include "raw" data with derivative products
  8 For example a grid gravity readings in addition to a colored image with RGB values
* Include basic metadata
  * Data source, URL if online / public domain
  * Projection
  * Licensing and copyright information if applicable
* Consistency

## Geology
* Consistent geologic map appropriate for the scale of the study area 
* Prefer lithology over formational names
* Include rheology and reactivity attributes if known
* Build [Topology](https://en.wikipedia.org/wiki/Geospatial_topology) if contact relationships are important
* Classify structures according to type, importance
* Include alteration layer(s) if known

## Geochemistry
* Include raw data and derivative products such as factor scores, interpretive maps, etc. 
* Normalize data where possible so it's leveled across analytical methods and surveys
* Include proxies for geochemistry (i.e. MRDS commodities)

## Geophysics
* Include raw data, derivatives, and interpretations (i.e. manual lineament analysis)
* Include products that target different depths and scales
* Common datasets are gravity and magnetics
