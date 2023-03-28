# Classification Landsat 8 image with Random Forest

##Prerequisites

The project is completed in a Windows 10 computer with Python 3 installed. It is convenient to install the libraries in a separate
conda environment to avoid ambiguous errors that could arise during the project. The following Python packages should be installed on the computer. 

-	Numpy
-	Pandas
-	Geopandas
-	Rasterio
-	Shapely
-	Matplotlib
-	EarthPy
-	Scikitlearn
-	Seaborn

The Landsat 8 image is taken over Toledo, Ohio, USA area and some areas of the image are covered with clouds. The image is classified in the project with Random Forest classification algorithm. Seven bands of the image 
subset were used for the study. Feature importance tool of Random Forest is used to identify the order of feature importance for the classification. 

Presence of the clouds in the image provided challenges for classification because of the variation of clouds and shades of clouds led to misclassify the features on the earth’s surface.
