# ahsi_thesis_gee
This code is an example of how to use s2cloudless in the JavaScript code editor of Google Earth Engine. The main code is from https://developers.google.com/earth-engine/tutorials/community/sentinel-2-s2cloudless. It extracts the Sentinel-2A data for a specified region of interest (in my case, Mpala Research Centre in Kenya), and removes clouds using s2cloudless. I added a final portion that calculates NDVI and exports the resulting TIFF to Google Drive. 

The original purpose of this code was to extract NDVI data on zebra and cattle grazing locations. This was then compared to ground truth data on grass quality and a positive linear relationship was found. As a result, I was able to use NDVI instead of manually measured grass quality which is a very time-consuming process. 

Thanks to Prof. Dan Rubenstein and Max Gotts for major help throughout this process.

**N.B.**
I believe there is a way to make the data more precise using the `clip()` function because this code currently creates a box around the region of interest. 
