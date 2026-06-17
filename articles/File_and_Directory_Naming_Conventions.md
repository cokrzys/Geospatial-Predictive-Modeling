# File and Directory Naming Conventions
[Open the Most Recent Version on GitHub](https://github.com/cokrzys/Geospatial-Predictive-Modeling/blob/main/articles/File_and_Directory_Naming_Conventions.md)

## General
* Underscores over spaces
  * Spaces are less legible and often cumbersome on the command line
* lowercase over Mixed or camelCase
  * Case is more applicable in documents, less in data files
* Descriptive names over codes
  * If you have to lookup or think too much about a code it's not useful
* Prioritize filenames over directory names
  * Filenames are "stickier" than directories
* Avoid renaming source data just for convention
* Filenames should stand alone
* Treat rules as Guidelines over rigid consistency

## A Filename Convention
1. prefix = short project name or abbreviation
2. body = longer free form descriptive data name
3. suffix(es) = one or more "standard" suffix(es) that help classify or distinguish similar files from each other
4. extension = data format

```bash
# MRDS data for the world, points, lat-long WGS84 (EPSG 4326), shapefile
world_mrds_pt_4326.shp

# MRDS data for the world, points, web mercator projection, shapefile
world_mrds_pt_3857.shp

# Colorado geology 1:500K, polygons, WGS 84 / UTM zone 13N (EPSG 32613), shapefile
co_geology_500k_pl_32613.shp

# Colorado geology 1:500K, lines, WGS 84 / UTM zone 13N (EPSG 32613), shapefile
co_geology_500k_ln_32613.shp
```

### Potentially Useful Suffixes
1. Data type
   * pt = points
   * ln = lines
   * pl = polygons
   * rs = raster (often redundant via the extension and can be left off)
2. Projection
   * EPSG codes are a solid standard and a concise descriptor for the coordinate system
3. Scale

```bash
# raster examples
```
## Directories

