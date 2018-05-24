# Mahmoud-Nazzal
Ph.D.
Wavelet-Domain Dictionary Learning-Based Single Image Superresolution Algorithm
Version 1.0
By: Mahmoud Nazzal and Huseyin Ozkaramanli
To recreate the findings reported in: 
M. Nazzal and H. Ozkaramanli, “Wavelet-domain dictionary learning-based single  image superresolution”, Signal Image and Video Processing, 
Springer, vol.  9, no. 7, pp. 1491-1501, Oct. 2015
This code is based on the source code provided by: Zeyde et al. , which can be found online at: http://www.cs.technion.ac.il/~elad/software/

The routines work as follows:

Demo_proposed_DWT_domain_DL.m
Trains DWT dictionaries over the training images located in the folder (Training_Images), and saves them as attributes in the struct (conf)

First: add training images to the folder (Training_Images)
Also: add test images tio the folder (Test_Images)

Demo_proposed_SR_algorithm.m
Simulates image super-resolution with the images located in the folder (Test_Images) via the proposed algorithm and bicubic interpolation.  
Results are compared in terms of PSNR and SSIM. It will create a folder (Results) where its stores the image recontructionsa nd whte PSNR 
and SSIM values.

Feel free to use or modify the code for personal, scientific and non-commercial purposes. Please cite the following work:

M. Nazzal and H. Ozkaramanli, “Wavelet-domain dictionary learning-based single image superresolution”, Signal Image and Video Processing,
Springer, vol. 9, no. 7, pp. 1491-1501, Oct. 2015

Contact: mahmoud.nazzal@emu.edu.tr, mahmoud.nazzal@ieee.org
