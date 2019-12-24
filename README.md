## These data have been replaced by data now found here:
https://github.com/UBCGeodata/ubc-geospatial-opendata/tree/master/ubcv/locations

ubcv-buildings
==============

Buildings at UBC Vancouver. Data are current, updates ongoing by C+CP.
The building data model and numbering are have changed significantly since the
last update. The data model is still undergoing review and may change
more in the near future. Addresses and building data as POI point data can be found in the ubcv-locations dataset.

Field descriptions can be found in the metadata directory.

Datasets
--------
### ubcv_buildings
* Campus buildings. A 'building' here follows from classroom codes in most cases. Buchannan (BUCH) is one code and one building.
### ubcv_subbuildings
* Campus building sections. Campus buildings can have wings and other sections.
   Buchannan has A, B, C, D, E sections. Additions and penthouses are
   not considered separate sections and not included here.
### ubcv_buildings_uc
* Buildings that are currently under construction.
### ubcv_building_records
* Each project generated a distinct set of records. A building may have many additions done as different projects, each with a different set of records. Many UBC operations datasets consider each addition a separate building. The primary key REC_ID should join 1:1 with such datasets.

Files Provided
--------------
* Provided in geojson, tableau, and ESRI file geodatabase formats.
* FGDB is ESPG:26910/UTM10N, geojson is lat/long(ESPG:4326).
* csv data has lat/long columns.

License
-------
* This data is made available under the Public Domain Dedication and License v1.0 whose full text can be found at: [http://www.opendatacommons.org/licenses/pddl/1.0/](http://www.opendatacommons.org/licenses/pddl/1.0/)

About
-----
* More information about UBC's geospatial data on GitHub can be found [here](https://github.com/UBCGeodata/opendata)
* There is some info about how to view and download data at the link above.
