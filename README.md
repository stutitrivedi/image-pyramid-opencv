# image-pyramid-opencv

This project demonstrates the construction of Gaussian and Laplacian pyramids using OpenCV. Image pyramids are a fundamental concept in computer vision, used for multi-scale image processing, blending, and object detection.

Problem Statement

Image pyramids provide a framework to process images at multiple resolutions. The objective of this assignment is to construct both Gaussian and Laplacian pyramids for a given image and understand how image resolution and detail change across levels.

Solution Overview

This notebook performs the following tasks:

Loads an input image using a relative path.

Constructs a Gaussian pyramid by repeatedly downsampling the image.

Constructs a Laplacian pyramid by subtracting upsampled images from previous levels in the Gaussian pyramid.

Visualizes and saves each level of the pyramids to understand the effect of resolution changes.

Key Features

Gaussian and Laplacian pyramids built using OpenCV functions

Each pyramid level stored and displayed

Input and output images handled using relative paths

Code includes comments explaining each step

Project Structure

image-pyramid-opencv/

CVPyramid.ipynb : Jupyter Notebook with full pyramid implementation

input_image.jpg : Image used to generate pyramids

gaussian_level_*.png : Output images from Gaussian pyramid levels

laplacian_level_*.png : Output images from Laplacian pyramid levels


Requirements

Python 3.x

numpy

opencv-python

matplotlib
