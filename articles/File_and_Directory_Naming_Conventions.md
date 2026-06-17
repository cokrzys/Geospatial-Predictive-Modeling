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
* Guidelines over rigid consistency

## A Filename Convention
1. prefix = project or study area abbreviation
2. body = longer free form descriptive data name
3. suffix(es) = one or more "standard" suffix(es) that help classify or distinguish similar files from each other
4. extension = data format

```bash
# MRDS data for the world, points, lat-long WGS84 (EPSG 4326)
world_mrds_pt_4326.shp
```
## Directories

