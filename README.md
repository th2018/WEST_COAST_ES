# attendee.rmd: #
Help identify attendee expertises

CENSUS_TIGER.ipynb: 
This Python code downloads the 2025 US state boundaries from the Census Bureau's TIGER dataset, filters the data to include only the states of Washington (WA), Oregon (OR), and California (CA), and exports the resulting GeoDataFrame as a GeoPackage file named "WA_OR_CA.gpkg".

national_forests_explode.ipynb: Explode multi-part geometries into multiple single geometries.

intersect.ipynb: 
This code loads two boundary datasets, selects all forest polygons that intersect the combined WA–OR–CA boundary polygons, and then saves the resulting subset as a new shapefile.

mask_boxplot.ipynb:
This code extracts pixel values from a raster within each polygon of a GeoDataFrame, collects them into a long-format DataFrame labeled by polygon, computes the median per polygon to sort them, and then creates a boxplot showing the distribution of raster values for each polygon ordered by increasing median.

mtbs_burn_count.ipynb:
rasterizes MTBS polygons into a grid where each pixel records how many wildfire polygons overlap it, then saves the result as a GeoTIFF and reports summary statistics.

terraclimate.ipynb:
The code extracts the time slice of the Climatic Water Deficit variable from a TerraClimate NetCDF file and exports it as a properly georeferenced single-band GeoTIFF.
