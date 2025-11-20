
CENSUS_TIGER.ipynb: This Python code downloads the 2025 US state boundaries from the Census Bureau's TIGER dataset, filters the data to include only the states of Washington (WA), Oregon (OR), and California (CA), and exports the resulting GeoDataFrame as a GeoPackage file named "WA_OR_CA.gpkg".

This code loads two boundary datasets, selects all forest polygons that intersect the combined WA–OR–CA boundary polygons, and then saves the resulting subset as a new shapefile.
