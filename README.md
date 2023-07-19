# Breast_cancer_detection_using_matlab


This MATLAB code presents an image processing pipeline for the detection of breast cancer tumors in mammogram images. The process starts by loading an image in the JPEG format and performing preprocessing steps, including converting the image to grayscale and applying a median filter to reduce noise. Thresholding is then applied to convert the grayscale image into a binary image, followed by morphological operations for further refinement.

After obtaining the binary image with potential regions of interest (ROI), the code uses region properties, such as area, perimeter, eccentricity, and solidity, to extract features from the ROI. These features are used for classification using a simple threshold-based approach. If the area and eccentricity of a region exceed predefined threshold values, it is classified as a potential cancerous region.

The code then visualizes the original image, grayscale image, filtered image, and the detected regions. If any cancerous regions are found, their centroids are marked with red asterisks on the image. The number of detected tumors is displayed along with the classification result.

It is essential to note that this code provides a basic example of breast cancer tumor detection and does not utilize advanced machine learning models for classification. For improved accuracy and performance, more sophisticated classifiers can be integrated into the pipeline to achieve better detection results
