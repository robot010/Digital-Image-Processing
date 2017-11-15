# Digital-Image-Processing

**Traditional image processing implementation** 

Instructor: [Marvin Doyley](http://www.ece.rochester.edu/people/faculty/doyley_marvin/index.html)

## Introduction 
This course is a required image processing course at University of Rochester. 

## Course Assignment

- Itensity Transformation. 
  - *Histogram, Sampling and Aliasing*. 
  - [Assignment](https://github.com/Bato803/Digital-Image-Processing/blob/master/Itensity-Transformation/HW2_Fall2015.pdf), [My Implementation](https://github.com/Bato803/Digital-Image-Processing/blob/master/Itensity-Transformation/HomeWork2.ipynb)
  
- Spatial Filtering. 
  - *Median Filter, Low-Pass Filter, Fourier Transform and Gibbs Phenomenon* 
  - [Assignment](https://github.com/Bato803/Digital-Image-Processing/blob/master/Spatial-Filtering/DIP_HW3.pdf), [My Implementation](https://github.com/Bato803/Digital-Image-Processing/blob/master/Spatial-Filtering/HW3-Spatial%20Domain%20Filtering.ipynb)
  
- Fourier Domain Filtering
  - *Gaussian Low-pass, High-Pass, Band-Pass Filter; Butterworth Low-Pass, High-Pass Filters*. 
  - [Assignment](https://github.com/Bato803/Digital-Image-Processing/blob/master/Fourier-Domain-Filtering/ECE447_Fall2015_HW4.pdf)，[My Implementation](https://github.com/Bato803/Digital-Image-Processing/blob/master/Fourier-Domain-Filtering/HomeWork%204.ipynb)
  
 - Image Restoration and Reconstruction
    - *Image contamination with various filtering*
    - *Radon and Inverse Radon transformation*
    - *Reconstruct original image from contaminated image*
    - [Assignment](https://github.com/Bato803/Digital-Image-Processing/blob/master/Image-Restoration-Reconstruction/ECE447_Fall2015_HW5.pdf)，[My Implementation](https://github.com/Bato803/Digital-Image-Processing/blob/master/Image-Restoration-Reconstruction/HomeWork%205%20.ipynb)

- Morphological Image Processing
  - *Image dilation, erosion, opening and closing*
  - [Assignment](https://github.com/Bato803/Digital-Image-Processing/blob/master/Morphological-Image-Processing/ECE447_Fall2015_HW5(1).pdf), [My Implementation](https://github.com/Bato803/Digital-Image-Processing/blob/master/Morphological-Image-Processing/HomeWork%206.ipynb). 
  
- Image Registration
  - *Affine Transformation, Projective Transformation*
  - [Assignment](https://github.com/Bato803/Digital-Image-Processing/blob/master/Image-Registration/ECE447_Fall2015_HW7.pdf), [My Implementation](https://github.com/Bato803/Digital-Image-Processing/blob/master/Image-Registration/HomeWork%207.ipynb). 

- Final Project: Image Registration for High Dynamic Range Image Generation
  - Generated High Dynamic Range Image from a series of low dynamic range images by doing [global image registration](https://github.com/Bato803/Digital-Image-Processing/blob/master/Final-Project/global_registration.ipynb), image de-ghosting(https://github.com/Bato803/Digital-Image-Processing/blob/master/Final-Project/Ghost%20Detection-Entropy%20based.ipynb), and [multi-resolution image integration](https://github.com/Bato803/Digital-Image-Processing/blob/master/Final-Project/Histogram-based.ipynb). 
  - Performed median threshold bitmap algorithm to detect ghosting area and highlight the ghosting area by using morphological image processing and cluster labelling.
  - Calculated the contribution of each image to the final image based on three parameters: contrast, saturation and exposedness. Obtained three weight maps containing the weight of every pixel of each image. 
  - Blended the images together by multi-resolution image blending algorithm, generated the final result by collapsing the Laplacian pyramid of original images and Gaussian pyramid of weight maps.  
Rating final result by comparing with commercial software Photomatix®.
  
