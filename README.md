# GrainBoundaryDetection
Machine Learning Image Processing Techniques on Grain Size and Grain Boundary Analysis


All of the files in this notebook can be run in google colab or just on your desktop on jupyter notebook

The name of the paper associated with this code is:

Machine Learning Image Processing Techniques on Grain Size and Grain Boundary Analysis


# KAGGLE DATASETS AVAILABLE

the kaggle datasets available to go with this code have some notebooks as well in kaggle that may help

The kaggle links are:

# Grains:

https://www.kaggle.com/datasets/peterwarren/exone-stainless-steel-316l-grains-500x

# Voronoi:

https://www.kaggle.com/datasets/peterwarren/voronoi-artificial-grains-gen

# GrainsV2:
This one has the manually segmented images as well

coming soon



# QUICK CODE Explanation for each code:

most explanations are given in the code, it is well commented
also the paper can be used too:
Machine Learning Image Processing Techniques on Grain Size and Grain Boundary Analysis


# Grain Intercept Measurement Method Grad.ipynb

Paper section 2.2

Gradient based image segmentation is also possible to separate the grains from
the grain boundaries. The gradient based approach will identify sharp changes
in pixel intensity, and it will classify those areas as an edge. There are several
mathematical tricks to determine the best way to detect this change in pixel
intensity, many of which involve taking the first or second derivative. The
method often considered to be the most robust is the ”Canny Edge Detection
Method,” developed by John Canny [14]. The basic process is to first to convert
the image to greyscale and then apply a Gaussian filter to smooth the image.
The gaussian filter makes the image slightly more blurry. This reduces the
amount of noise that will be detected in the process. Next the pixel intensity
gradient is calculated (the first derivative of the image). Lower changes in pixel
intensity can be filter out, unless they directly connected to a high change in
pixel intensity.


# Grain Intercept Measurement Method HED.ipynb


# Grain Intercept Method Manual Thresholding.ipynb


# PLANIMETRIC SHAPES.ipynb


# Planimetric Method Areas.ipynb
