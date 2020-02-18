# Vancouver Open Data Maps using folium

## Requirements

```bash
conda install --quiet --yes --channel conda-forge \
    'pyodbc=4.0.28' \
    'geopandas=0.6.3' \
    'folium=0.10.1'
```


## Try it out

* [Basic map with zoning polygons](van_map.html)
* [Choropleth of area](van_map_zoning-area.html)
* [Colored map of zoning category](van_map_zoning-category.html)
* [Colored map of zoning category with popup](van_map_zoning-category-popup.html)


## Data Sources:

* https://opendata.vancouver.ca/explore/dataset/zoning-districts-and-labels/export/
* https://opendata.vancouver.ca/explore/dataset/property-tax-report/export/
* https://opendata.vancouver.ca/explore/dataset/elevation-contour-lines-10-metre-contours/information/?disjunctive.elevation
* https://opendata.vancouver.ca/explore/dataset/road-ahead-upcoming-projects/export/
* https://opendata.vancouver.ca/explore/dataset/goads-fire-insurance-map-1912-georectified/export/?location=11,49.32915,-123.13992
* https://data.vancouver.ca/datacatalogue/index.htm
