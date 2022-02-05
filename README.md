# Medical Image Preprocessing

The main objective of pre-processing is the improvement of image data that suppresses unwilling distortions or enhances some image features important for further processing. Images which are to be passed to the machine learning model in later stages should not contain any noise, biases or missing data as that could lead to the generation of incorrect results. Thus, appropriate image pre-processing methods needs to be applied in order to enhance the image quality which would help us to analyze the images better and to facilitate the extraction of image features which would be passed to the machine learning model along with the pre-processed images for training and testing purposes.

## Normalization
Normalization in image processing is a typical process which changes the range of pixel intensity values. Its basic purpose is to convert an input image into a range of pixel values that are more familiar or normal to the senses, hence the term normalization. In our project the input CT scan DICOM images have intensity values lying beyond the required range of 0-255. 

## Binarization
Binarization in image processing is the process of converting a grayscale image into black-and-white, essentially reducing the information contained within the image from 256 shades of gray to two i.e. black and white. It is a form of segmentation whereby an image is divided into constituent objects.

## Histogram equalization
Histogram Equalization is a processing technique used to improve contrast in images. It accomplishes this by effectively spreading out the most frequent intensity values, i.e. stretching out the intensity range of the image. This method usually increases the global contrast of images when its usable data is represented by close contrast values. This allows for areas of lower local contrast to gain a higher contrast.

## Difference of Gaussian          
Difference of Gaussians (DoG) filtering is a feature enhancement algorithm that involves the subtraction of one Gaussian blurred version of an original image from another, less blurred version of the original. In the simple case of grayscale images, the blurred images are obtained by convolving the original grayscale images with Gaussian kernels having differing width. 

## Laplacian of Gaussian
The Laplacian is a 2-D isotropic measure of the 2nd spatial derivative of an image. The Laplacian is often applied to an image that has first been smoothed with something approximating a Gaussian smoothing filter in order to reduce its sensitivity to noise. 

## Median filtering
Median filtering is a nonlinear method used to remove noise from images. The median filter works by moving through the image pixel by pixel, replacing each value with the median value of neighbouring pixels. The pattern of neighbours is called the "window", which slides, pixel by pixel over the entire image.
