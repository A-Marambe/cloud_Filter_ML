# cloud_Filter_ML
why this code? 
there different ways of cloud masking of satellite images. Satellite images include QC band(Fmask algorithm), which is usable in cloud masking. In practical situations, it is not detecting some clouds and shadows correctly all the time. We can use well representative trainnig data set manually generated using a image processing software to train a model to classify the clouds and cloud shadows in images.

- Machine learning algorithms in remote sensing to filter clouds and shadows in satellite images 

This code read training data set in tabular format including lat/lon locations and cloud free, cloud or cloud shadow pixels clasess.
The project use the Random Forest Classifier as the algorithm
model predicts automatically cloud free, clody and cloud shadow location and write data back into rasters for the perpose of data visualization and cliping.

this method will easly picks up clouds and shadows of a large satellite data set, will be useful in bulk image analysis
