# Example images for the {pliman} package

This repository stores example images mainly focused on plant phenotyping, intended to assist in the use of the `{pliman}` package.

The availability of these mosaics is essential for the continued improvement of
tools like {pliman}. I would like to extend my gratitude to
[\@FilipeMathias](https://www.linkedin.com/in/filipe-matias-27bab5199/) and
[\@Alcinei Azevedo](https://www.expstat.com/) for providing various materials
related to high-throughput phenotyping, and to
[\@MaiconNardino](https://www.linkedin.com/in/maicon-nardino-091253268/),
[\@CaiqueSilva](https://www.linkedin.com/in/caique-machado-e-silva-404415154/),
[\@Arthur Bernardeli](https://www.linkedin.com/in/arthur-bernardeli-5a1a0b5a/),
and [\@Gustavo Nandi](https://www.linkedin.com/in/gustavo-nandi-035905127/) for
providing some orthomosaics used in this material.

Additionally, special thanks to 

# Folder Structure

## 1. ndsu
- `ndsu.tif`: A multispectral orthomosaic, originally available [here](https://github.com/diegojgris/draw-plots-qgis/blob/main/sampledata/MicaSenseMXRed_5bands.tif).
- `ndsu.rds`: A field shape containing drawn plots (6 rows and 15 plots per row).

## 2. dsm
- `dsm.tif`: A digital surface model from a soybean field.
- `dtm.tif`: A digital terrain model associated with the DSM.
- `mask.tif`: A mask for the mosaic to refine the analysis.
- `points.rds`: Sample points that can be used for interpolation with `pliman::mosaic_interpolate()`.
- `shapefile.rds`: Shapefile with field plots.

## 3. rice_field
- `rice_ex.tif`: An RGB orthomosaic from a rice field, originally available [here](https://github.com/aipal-nchu/RiceSeedlingDataset).
- `shp_rice.rds`: Shapefile containing the drawn plots (8 lines and 1 column).

## 4. lettuce
The images in this folder are originally available in described in [this
paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0274731).

- `lettuce.tif`: An image representing a lettuce field.
- `lettuce.rds`: A field shape containing plots for the lettuce field (18 rows and 4 columns).
- `field.png`: A visualization of the lettuce field, describing the used treatments.

## 5. potato
A potato breeding field kindly provided by [Gustavo Nandi](https://www.linkedin.com/in/gustavo-nandi-035905127/).

- `potato.tif`: An image of a potato field.
- `potato.rds`: A field shape containing plots for the potato field (13 columns and 16 rows).

## 6. orthomosaic
This folder contains orthomosaics and shapefiles related to a soybean field. An
special thanks to [Arthur
Bernardeli](https://www.linkedin.com/in/arthur-bernardeli-5a1a0b5a/) for
providing the raw images that were used to build the mosaics.
- `orthomosaic.tif`: A high-resolution orthomosaic image.
- `orthosmall.tif`: A cropped version of the orthomosaic.
- `orthomosaic.rds`: Raster data for orthomosaic analysis.
- `controlpoints.rds`: Control points for georeferencing.

## 7. wheat
This folder contains a multispectral orthomosaic from a wheat breeding trial and
was kindly provided by
[\@MaiconNardino](https://www.linkedin.com/in/maicon-nardino-091253268/) and
[\@CaiqueSilva](https://www.linkedin.com/in/caique-machado-e-silva-404415154/)
from UFV.

- `wheat.tif`: The orthomosaic file
- `wheat.rds`: The shapefile that contains two blocks. The first has 5 columns and 21 rows; the other one has 1 column and 3 rows.
