# ImageProcessing_Interpolation-functions
Affine transformation analysis using Python and OpenCV

A practical image processing assignment notebook that combines linear algebra, image inspection, bit-level compression, and affine transformation analysis using Python and OpenCV.

## Overview

This notebook is the second image processing exercise (`Tamrin2`) and focuses on several core topics in image processing and computer vision. It includes:

- solving a small linear algebra system
- loading and cropping images
- inspecting image metadata
- visualizing image histograms
- compressing images by removing the least significant bit
- estimating image rotation using edge and line detection

The notebook is structured as a step-by-step assignment with labeled questions and parts.

## Features

- **Linear Algebra Warm-up**  
  Solves a system of equations using NumPy.

- **Image Cropping and Inspection**  
  Loads images and crops them to a region of interest.

- **Histogram Analysis**  
  Visualizes and compares image histograms.

- **Bitwise Image Compression**  
  Demonstrates compression by zeroing out the least significant bit of each pixel.

- **Image Metadata Analysis**  
  Displays image dimensions, channel count, pixel count, and bit depth.

- **Rotation Estimation**  
  Detects edges and lines to estimate the rotation angle of an image.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- OpenCV (`cv2`)
- PIL
- Math

## Libraries Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import cv2
from google.colab.patches import cv2_imshow
from PIL import Image
import math
