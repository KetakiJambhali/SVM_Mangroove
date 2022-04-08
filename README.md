# SVM_Mangroove

Using SVM Classifier for land cover mapping using sentinel 2 and mapping mangrooves in Sunderbans.

We will be classifying mangrooves in Sunderbans, India for the year 2021.

Datasets : 

Esri land cover map (10m) for 2020

Sentinel 2 (Jan-2021)

Landsat 8 (Jan-2021)

Ground truth (samples) :

Stratified Random Sampling

100 samples per class

ten times the number of input variables (Jensen, 1996)

Label data preparation :

We will be using an already prepared training dataset that consists of polygons of each land use classification. These polygons were prepared by people using GIS digitizing methods (QGIS, ArcGIS, JOSM) with satellite imagery to trace over. The file is present as ground_truth.geojson. 



