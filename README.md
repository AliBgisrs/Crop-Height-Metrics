# Crop-Height-Metrics
This tool calculates statistical metrics of crop height using DSM and DEM layers in each plot. Make sure that your plot boundary layer has a field with the name of "New_ID" as plot number. Enjoy it
Project Title
[Calculate crop height statistical metrics based on DSM and DEM layers ]
Description
[if you are working with LIDAR or digital aerial photometry to extract the height of the plant, this tool would be helpful. For using this tool, you need to have a feature layer of the boundary of your location or the boundary of the plots that you are working on it. This layer should have a field with the name of New_ID that shows the unique ID for your plots (plot number). In addition, you need to have an image format for DSM and DEM layers as input]
 
Table of Contents
•	Installation
•	Usage
•	Contributing
•	License
Installation
[Download the tool and csv folder, put csv folder in your C drive.]
[Go to the insert tab of your ArcGIS PRO project]
 
[Select add folder and browse to the folder that you have saved your script and add that folder]
[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of CropHeightMetrics.atbx, then open it to find the script]
  

 
[Double click and open the script]
 
[Call the input feature layer (your plot boundries). Note: You should have a feature layer not shape file. Your feature layer should be a polygon.

 
Before running the tool you should paste csv folder in your C drive directory to save the results on there. 
 
Usage
if you are working with LIDAR or digital aerial photometry to extract the height of the plant, this tool would be helpful. For using this tool, you need to have a feature layer of the boundary of your location or the boundary of the plots that you are working on it. This layer should have a field with the name of New_ID that shows the unique ID for your plots (plot number). In addition, you need to have an image format for DSM and DEM layers as input. DSM and DEM layers should be in image format.
 
After running the tool an excel file will be created in your csv folder at your C drive. In addition, if you open 6.gdb at your ARCMAP you can see the resulted rasters and feature layers.
 
The tool calculates some important statistical metrics including: minimum, mean, maximum, Stdev, and percentiles of plant height in each plot.
 

 
Contributing
[Please run the script, use it and help me to improve the performance of that script using your valuable suggestions.]
License
About the Author
[Developed by Aliasghar Bazrafkan.]
Acknowledgments
[I would like to express my sincere appreciation to my supervisor, Dr. Paulo Flores, from North Dakota State University (NDSU), for providing invaluable support and guidance throughout the development of this script. His expertise and encouragement have been instrumental in making this project possible].
Contact
[Aliasghar.bazrafkan@ndus.edu]
Additional Notes
[https://sites.google.com/ndsu.edu/floreslab/home?authuser=0]
