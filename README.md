# Image_Processing_with_OpenCV
This repo is a intermediate to advance level Image processing code examples and guide with open cv in python

# Image Processing Concepts with OpenCV and Wand
This jupyter notebook consists of solid practical examples for multiple concepts of image processing.
## OpenCV
OpenCV is a great tool for image processing and performing computer vision tasks. It is an open-source library that can be used to perform tasks like face detection, objection tracking, landmark detection, and much more. It supports multiple languages including python, java C++.
## Wand
The Wand is an Imagick library for python. It supports the functionalities of Imagick API in Python 2.6, 2.7, 3.3+, and PyPy. This library not only helps in processing the images but also provides valuable functionalities for Machine Learning codes using NumPy.

### Gamma Correction
Gamma correction, which is used to display an image accurately onscreen, controls the brightness of an image and can be used to change the red-to-green-to-blue ratio,
Two examples are implemented for Gamma correction one with opencv and other with wand library.

### Deconvolution
Deconvolution is used to correct blurry images, which helps 
restore contrast. With blurred images, it is difficult to determine pixel 
intensity. To make this correction, we use what is called the point spread 
function (PSF).

#### Image deconvolution
we deconvolve an image using Richardson-Lucy deconvolution algorithm.

The algorithm is based on a PSF (Point Spread Function), where PSF is described as the impulse response of the optical system. The blurred image is sharpened through a number of iterations, which needs to be hand-tuned.

#### Image filters
#### Blurring examples given
1. Box Blur
2. Gaussian Blur
3. Median Blur 
4. Sharpening
5. Emboss

### Skimage Library
1. RGB to HSV
2. RGB to LAB

# Advanced Image Processing Using OpenCV
1. Blend two images
2. Changing Contrast and Brightness
3. Add text to images
4. Smoothing images with (MedianBlur, GaussianBlur, BilateralBlur)
5. Image Erosion
6. Image Dilation
7. Effect Image Threshold
8. Calculate Gradients
9. Perform Histogram Equalization

# Image Processing Using Machine Learning
## Feature mapping using the scale-invariant feature transform (SIFT) algorithm
1. Find and constructing a space to ensure scale invariance
2. Find the difference between the gaussians
3. Find the important points present inside the image
4. Remove the unimportant points to make efficient comparisons
5. Provide orientation to the important points found in step 3
6. Identifying the key features uniquely.

## Image Registration Using the RANSAC Algorithm
Suppose we have two images of a single place from an aerial view. One 
image depicts the place using satellites whereas the second one shows a 
part of the same image using drones. Satellite images get updated in terms 
of years, whereas drone images are taken much more frequently. So, there 
may be a situation in which the drone image captures developments not 
see in the satellite image. In this scenario, we may want to put the drone 
image in exactly the same place where it belongs in the satellite image, 
but also show the latest updates. This process of putting one image over 
the other, at exactly the same place where it is present, is called image 
registration.

RANSAC is one of the best algorithms to use for image registration, 
which consists of four steps:
1. Feature detection and extraction
2. Feature matching
3. Transformation function fitting
4. Image transformation and image resampling

## Find Palm Lines of Hand
Find lines of hand make them prominent on the image
## Detect faces
Detect faces in the image.

## Recognize Face of person
Train on some data and see the results


Notes:
The datasets used are also in the repo incase you want to test on similar data.

Access the notebook on Google Colab:
https://colab.research.google.com/drive/1uYMU8Zv7TS1w5q481ajPEZ_A_73DvoPV?usp=sharing
