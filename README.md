# Shape and Color Detection with OpenCV

A computer vision project that detects geometric shapes and identifies their dominant colors using OpenCV and K-Means clustering.

## Features

* Shape detection using contour analysis
* Polygon approximation using `cv.approxPolyDP()`
* Object masking using contours
* Dominant color extraction using K-Means clustering
* Classification of:

  * Triangle
  * Rectangle
  * Hexagon
  * Circle
* Dominant color recognition:

  * Red
  * Green
  * Blue

## Technologies Used

* Python
* OpenCV
* NumPy

## Processing Pipeline

1. Read image
2. Convert image to grayscale
3. Apply thresholding
4. Detect contours
5. Approximate contours using `approxPolyDP`
6. Create a mask for each detected object
7. Extract object pixels
8. Apply K-Means clustering
9. Find dominant color
10. Classify shape and color
11. Display results on image

## Concepts Practiced

* Image Processing
* Contour Detection
* Shape Analysis
* Image Masking
* K-Means Clustering
* Dominant Color Extraction
* Object Classification

## Example Output

Rectangle Red

Hexagon Green

Circle Blue

Triangle Red

## Future Improvements

* Support for more colors
* HSV color space classification
* Distinguish square, rectangle, and rhombus
* Circularity-based circle detection
* Real-time webcam processing

## What I Learned

This project helped me understand:

* How contours represent object boundaries
* How masks isolate objects from an image
* How K-Means can be used for color clustering
* How polygon approximation is used for shape detection
* How multiple computer vision techniques can be combined into a complete pipeline
