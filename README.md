# VishnuSuresh27.github.io
This is the portfolio website of select projects I have built. This website is under construction. 

## Colorizing the Prokudin-Gorskii Photo Collection
Sergei Mikhailovich Prokudin-Gorskii was a Russian photographer who pioneered color photography in the early 20th century. He took thousands of color pictures, each a series of three exposures of a scene onto a glass plate using red, green, and blue filters. Each of these plates have been digitized as a single image containing the different plates aligned vertically on each other, with the blue plate on top, the green plate in the middle, and the red plate on the bottom.

The goal of this project is to take the digitized versions of those glass plates and to employ image processing techniques to align the plates to produce a full color photograph with as few artifacts as possible.
This index.html contains a detailed report and image results for the colorization and alignment algorithms. Specifically, Project Overview, Details of the Algorithm, Results with colored images and Bells and Whistles (Gradient Detection Maps), 

## Fun with Filters and Frequencies
This project explores the multifarious ways of utilizing image filters and image frequency bands to come up with unique and interesting results.
These include Edge Detection using Derivative of Gaussian (DoG) Filters, hybridizing images so that what you view changes as a function of your distance from the image, image sharpening, and multi-resolution blending. The power of these methods enables us to put creative ideas into picture! (You might see a Wimbledon Champion you've never heard of before!)

## Face Morphing
In this project, I produce a "morph" animation of my face into someone else's face (Roger Federer), compute the mean of a population of faces, from the open source FEI database and extrapolate from this population mean to create a caricature of myself. I also use image warping/morphing to come up with a new image of myself with a hypothetical change in gender, among other Bells and Whistles.

## Image Warping and Mosaicing
In this project, I experiment with Image Homography - projecting an image on another plane surface that is not the image plane. An alternative name for this Perspective Projection Transformation. Finally, I will take three groups of three photographs (all at the same Center of Projection) and create an image mosaic (similar to an image panaroma taken on an iPhone) by registering, projective warping, resampling, and compositing them

## Power of Diffusion Models
In this project, I explore the power of diffusion models in generating high-quality images. In Part A, I generate images using a pretrained diffusion model called DeepFloyd. In Part B, I train a diffusion model on PyTorch's MNIST dataset.