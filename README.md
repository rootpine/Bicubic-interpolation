# Bicubic-interpolation
This repository is for simple implementation of 'Bicubic-interpolation for images' (Python3). 

## Table of contents
  * [Formulation](#Formulation)
  * [Example](#Example)
  * [Requirement](#Requirement)
  * [Installation](#Installation)
  * [Usage](#Usage)
  * [Reference](#Reference)
  * [Author](#Author)
  
## Formulation
  * Interpolation kernel  
  ![Formulation](./formulation.png)  
  
  * Interpolation  
  Use the values of 16 pixels around the new pixel dst(x,y). (x,y) shows the location of pixels. 
  ![Formulation2](./formulation2.png)  
  Here, f means the values of pixels. x1, x2, x3, x4 are the distance of x direction from new pixel to near 16 pixels. y1, ... are the distance of y direction. 
  
## Example
  * Upscale input image 2 times (ratio = 2)  
  Input image (216x216)  
  ![Input image](./butterfly.png)  
  Output image (512x512)  
  ![Output image](./bicubic_butterfly.png)
  
## Requirement
  * Python 3.5.2 or more 

## Installation
  `$ git clone https://github.com/rootpine/Bicubic-interpolation.git`

## Usage
   1. `$ python3 bicubic.py`

## Reference
  * R. Keys, "Cubic convolution interpolation for digital image processing," in IEEE Transactions on Acoustics, Speech, and Signal Processing, vol. 29, no. 6, pp. 1153-1160, December 1981. URL: <http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1163711&isnumber=26156>


## Author
  [@rootpine](https://github.com/rootpine/)
