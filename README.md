# Crop-Height-Metrics
This tool calculates statistical metrics of crop height using DSM and DEM layers in each plot. Make sure that your plot boundary layer has a field with the name of "New_ID" as plot number. Enjoy it
Project Title

[Calculate crop height statistical metrics based on DSM and DEM layers ]

Description

[if you are working with LIDAR or digital aerial photogrametry to extract the height of the plant, this tool would be helpful. For using this tool, you need to have a feature layer of the boundary of your location or the boundary of the plots that you are working on it. This layer should have a field with the name of New_ID that shows the unique ID for your plots (plot number). In addition, you need to have an image format for DSM and DEM layers as input]

 ![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/0bb313e2-a376-4bf5-9272-e085e0065293)

 

Table of Contents

•	Installation
•	Usage
•	Contributing
•	License

Installation

[Download the tool.]
[Go to the insert tab of your ArcGIS PRO project]

![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/04e84566-ff7e-45b3-9adc-d99b5f44d86f)

 
[Select add folder and browse to the folder that you have saved your script and add that folder]
[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of CropHeightMetrics.atbx, then open it to find the script]
  
![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/465303e9-234a-4026-80d2-85923a43673b)


 ![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/051f038b-2aae-4a24-b263-aae44965f66c)
 

[Double click and open the script]

![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/ccd3e652-bc64-42ae-a97a-2ef31f2cf35c)


 
[Call the input feature layer (your plot boundries). Note: You should have a feature layer not shape file. Your feature layer should be a polygon.

 ![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/ce92cd93-a76b-4520-a9f6-a917a2a75585)

 


 

Usage
if you are working with LIDAR or digital aerial photogrametry to extract the height of the plant, this tool would be helpful. For using this tool, you need to have a feature layer of the boundary of your location or the boundary of the plots that you are working on it. This layer should have a field with the name of New_ID that shows the unique ID for your plots (plot number). In addition, you need to have an image format for DSM and DEM layers as input. DSM and DEM layers should be in image format.

![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/2d571eee-16f5-4321-8be5-b73de4e49988)

 
After running the tool an excel file will be created in your directory folder. In addition, if you open 66.gdb by your ARCMAP, you can see the resulted rasters and feature layers.

![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/3d12cd09-36d8-42c5-9195-59931d45b02c)


 
The tool calculates some important statistical metrics including: minimum, mean, maximum, Stdev, and percentiles of plant height in each plot.

 
![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/4b443427-3ca7-4f9b-8ede-e07f67379511)


![image](https://github.com/AliBgisrs/Crop-Height-Metrics/assets/109620013/a2f9f582-89c4-4724-9cbe-ffbae94128b8)

 

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
