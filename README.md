# Example images for the {pliman} package

This is a helper repository to store example images, mainly focused on plant phenotyping. 

# Folder 'pliman' 
  - NDSU
    * `ndsu.tif` a  multispectral orthomosaic, originally available [here](https://github.com/diegojgris/draw-plots-qgis/blob/main/sampledata/MicaSenseMXRed_5bands.tif)
    * `ndsu_shp.shp`, `ndsu_shp.dbf`, `ndsu_shp.prj`, `ndsu_shp.shx`, and `ndsu_shp.cpg` are the shapefiles that contains the drawn plots (6 rows and 15 plots per row)
    
  - dsm
    * `dsm.tif` a digital surface model originally available at the [FIELDimageR pipeline](https://github.com/OpenDroneMap/FIELDimageR)
    * `dsm_shps.rds` a fieldshape with 144 plots (9 rows and 16 columns) that can be used to analyze the mosaic
    * `dsm_points.rds` a shapefile with sample points that can be used to interpolate the mosaic using `pliman::mosaic_interpolate()`
  
  - rice_field
    * `rice_ex.tif` an RGB orthomosaic from a rice field originally available [here](https://github.com/aipal-nchu/RiceSeedlingDataset).
    * `rice_ex.shp`, `rice_ex.dbf`, `rice_ex.prj`, `rice_ex.shx`, and `rice_ex.cpg` are the shapefiles that contains the drawn plots (8 lines and 1 column)
