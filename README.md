# geo_notebooks
A (nascent) collection of jupyter notebooks of various geo data processing workflows, collating from various other places and projects

Create a suitable environment using e.g. 

`conda env create -f conda_env/geodev_38_environment.yml`

(exported using `conda env export --from-history`)

### Notebooks

* [lagged_point_raster_extraction](lagged_point_raster_extraction.ipynb)
Extracting a time-series of raster values at point locations, for periods relative to the point's sampling dates. Data table manipulation using pandas
