# Biodiversity Intactness Index change in Phoenix, AZ

## About
Due to a rapid increase in developed land, Phoenix, Arizona has seen changes in biodiversity. This repository contains a notebook `biodiversity-intactness-indez.ipynb` where the impacts on biodiversity due to urban sprawl are examined by analyzing the changes in Biodiversity Intactness Index(BII).


## Repository Structure
```
|── biodiversity-intactness-index 
|└── README.md
|└── biodiversity-intactness-index.ipynb
|└── images/  
|  └── bii_phoenix.png
|  └── phoenix_arizona_map.png
|└── .gitignore  
|  └── data/ 
|    └── tl_2024_04_cousub
|      └── tl_2024_04_cousub.cpg
|      └── tl_2024_04_cousub.dbf
|      └── tl_2024_04_cousub.prj
|      └── tl_2024_04_cousub.shp
|      └── tl_2024_04_cousub.shp.ea.iso.xml
|      └── tl_2024_04_cousub.shp.xml
|      └── tl_2024_04_cousub.shx
```


## Data
The first dataset is the Biodiversity Intactness Index(BII) Time Series. This data comes from the [Microsoft Planetary Computer STAC catalog](https://planetarycomputer.microsoft.com/dataset/io-biodiversity). In the analysis we use the 2017 and 2020 rasters.

The second dataset is the [Census Bureau](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2024&layergroup=County+Subdivisions) County Subdivisions shapefile for Arizona. The Phoenix subdivision was downloaded from this shapefile.

An ESRI National Geographic style world basemap was used to show the Phoenix subdivision in its broader geographic context.

## References

1. Microsoft Planetary Computer. (n.d.). IO biodiversity dataset. Retrieved December 3, 2024, from https://planetarycomputer.microsoft.com/dataset/io-biodiversity

2. U.S. Census Bureau. (2024). Arizona county subdivisions: tl_2024_04_cousub.shp [Shapefile dataset]. Retrieved from https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2024&layergroup=County+Subdivisions 

3. 3. Esri. (n.d.). National Geographic Style [Basemap]. ArcGIS. Retrieved December 6, 2024, from https://hub.arcgis.com/maps/3d1a30626bbc46c582f148b9252676ce/explore【6】.