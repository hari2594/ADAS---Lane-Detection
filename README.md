# ADAS - Lane Detection       ![](https://img.shields.io/badge/Haribaskar-Dhanabalan-brightgreen.svg?colorB=#ADFF2F)
The problem I have solved in this code is to take a simple video as input data and process it to detect the lane within which the vehicle is moving. Then we will find a representative line for both the left and right lane lines and render those representations back out to the video as a blue overlay.

*Computer vision* is an area of computer science devoted to the extraction and processing of structured information from mostly-unstructured image data. We are going to use *OpenCV* to process the input images to discover any lane lines held within and also for rendering out a representation of the lane. Additionally, images are really just dense matrix data, so we will use numpy and matplotlib to do transformations and rendering of image data. 

---
## The following techniques are used:
1. Canny Edge Detection
2. Region of Interest Selection
3. Hough Transform Line Detection

## Lane Detection: Demo Video

[![Watch the video](http://i3.ytimg.com/vi/hSjBazKT-L0/maxresdefault.jpg)](https://www.youtube.com/watch?v=hSjBazKT-L0)

---
## Contributing

Patches are welcome, preferably as pull requests.

---
