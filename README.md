# Gdal Exercises by SpatialThoughts
This will be my reflection series for this gdal learning to have a actual learning path

## Some few commands
! = for shell type codding to avoid pythonic way
^ = for new space
> = output.txt

# gdal command extensions
-o = output
-of = Option
-co = compress
-a_ullr = bounding box
-a_srs = projection (EPSG:4326)
-ot = data type (Byte, Float)


## basic Commands
1. gdalinfo --version
2. gdalbuildvrt
3. gdal_translate
5. gdalwrap
6. gdaldem hillshade

### gdal scripts
1. python %CONDA_PREFIX%\Scripts\gdal_calc.py
2. python %CONDA_PREFIX%\Scripts\gdal_pansharpen.py


# OGR Tools
ETL pipelines, spatial sql queries

## ogr commands
1. ogrinfo
2. ogr2ogr

### gdal scripts
-python %CONDA_PREFIX%\Scripts\ogrmerge.py
-python %CONDA_PREFIX%\Scripts\ogr_layer_algebra.py

### ogr command extensions
-al = all layers
-so = summary only
-oo X/Y_POSSIBLE_NAMES = for csv to points
-nln = rename
-t_srs = new projection
-overwrite_ds
-f = file (TYPE file_name.type)

### spatial queries/methods
-dialet SQLITE

