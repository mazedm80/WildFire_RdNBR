Lionshead WildFire and compariosn between dNBR vs RdNBR
================
Mir Mazedur Rahaman
2/7/2021

## WildFire_RdNBR.Rmd
This repo houses an R Markdown Document that has code chunks for
- Pre Processing of Landsat images of Pre fire and Post fire.
- Calculating pre and post NBR and dNBR.
- Classification of dNBR.
- Calculating RdNBR
- Classification of RdNBR
- Compare dNBR and RdNBR
This script is currently used for my Remote Sensing III masters course. Since this script has not been fully vetted, caution should be taken if used for research.

## Input files stored in the /data folder:
* Since the Landsat file is too big the **/data** folder is ignored

## Output files stored in the /output folder:
* Due to big files the **/output** folder is also ignored

## Library
To run the Rmd file 'rmarkdown' packeg is required. To run the WildFire_RdNBR.Rmd script the `raster` `RStoolbox` `rgdal` and few other packages are required which is included in Script.