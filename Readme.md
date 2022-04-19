# Landsat_9_LC_classification
# Landcover classification using Landsat 9


## Project Structure
The descriptions of principal files in this project are introduced as follows:
* training_data : include training_data_points that are randomly scattered across the area of interest. The values of Label image (ESRI landcover image ) and training image (Landsat 9 ( Multispectral and PCA reduced Image)) are extracted to randomly scattered training points. Training points are converted to excel data for modelling 

* Landsat 9 classification.ipynb : notebook for training Random forest model
  
## Principal Environmental Dependencies
* sklearn
* numpy
* pandas
* geopandas
* rasterio
* matplotlib


## Original Landsat 9 True Color Composite 
<img src="image/Capture.PNG" width="700" height="500" > 

## PCA performed Image
 <img src="image/12Capture.PNG" width="700" height="500" > 
 
## Random Points over label data
 <img src="image/1.PNG" width="700" height="500" > 

## Classification Report
<img src="image/classification_report.PNG" width="700" height="300" > 


## OutPut Landcover Map
<img src="image/pred compare.PNG" width="700" height="300" > 
