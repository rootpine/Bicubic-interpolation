# Bicubic-interpolation
This repository is for simple implementation of 'Bicubic-interpolation for images' (Python3). 

## Table of contents
  * [Example](#Example)
  * [Requirement](#Requirement)
  * [Installation](#Installation)
  * [Usage](#Usage)
  * [Reference](#Reference)
  * [Author](#Author)
  
## 
  ```math
  u(s) = \left\{ \begin{array}{ll}
  (a + 2){|s|}^{3} - (a+3){|s|}^{2} + 1 & (0 < |s| \le 1) \\
  -a{|s|}^{3} -5a{|s|}^{2} + 8a{|s|} -4a & (1 < |s| \le 2)\\
  0 & (2 < |x|)
  \end{array} \right.
  ```
## Example
  * Upscale input image x2  
  ![Input image](./butterfly.png)*Input image (216x216)*
  ![Output image](./bicubic_butterfly.png)*Output image (512x512)*

## Requirement
  * Python 3.5.2 or more 

## Installation
  * `$ git clone https://github.com/rootpine/Bicubic-interpolation/`

## Usage
   1. `$ python3 bicubic.py`

## Reference
  * R. Keys, "Cubic convolution interpolation for digital image processing," in IEEE Transactions on Acoustics, Speech, and Signal Processing, vol. 29, no. 6, pp. 1153-1160, December 1981. URL: <http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1163711&isnumber=26156>


## Author
  [@rootpine][https://github.com/rootpine/]
