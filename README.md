# umgdy-ab-DEM-validation
ArcGIS ModelBuilder Tool for DEM validation

1. Extracts values from raster to point feature class (creates 'h_[name]' field).
2. Subtracts rastervalues from values in h_meas field (creates 'd_[name]' field).

Following fields in a point feature class are required:
* h_meas - with height values to compare with rastervalues,
* pt_id - with points IDs.

Requirements:
* Spatial Analyst extension
* This tool may not work properly with shapefiles, because ofnon-nullable fields.
* This toolbox was created in ArcGIS 10.4. You may not be able to open this toolbox in previous versions of ArcGIS, if the internal format of toolboxes was changed from release to release.
