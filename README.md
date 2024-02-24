
---

# Kidney Stone Detection on Ultrasonic Images

This project focuses on detecting kidney stones in ultrasonic images using image processing techniques. Implemented in MATLAB and Python using OpenCV, the project utilizes various computer vision methods to analyze ultrasonic images effectively.

## Dataset

The dataset used in this project can be found [here](https://www.ultrasound-images.com/kidneys/). 

## Kidney Stone Detection using MATLAB

This MATLAB-based project aims to detect kidney stones in ultrasonic images. The following steps were implemented:

1. **Input Image Visualization**: The input ultrasonic image is loaded and visualized using MATLAB.

2. **Image Preprocessing**: The image is preprocessed by converting it to grayscale and applying thresholding techniques to segment the kidney stone.

3. **Morphological Operations**: Morphological operations are performed to fill holes and remove background noise from the binary image.

4. **Region Extraction**: The filtered binary image is used as a mask to extract the kidney stone region from the original image.

5. **Intensity Adjustment**: The intensity of the extracted region is adjusted to enhance visibility and clarity.

6. **Noise Reduction**: Median filtering is applied to further reduce noise and smoothen the image.

7. **Thresholding**: A threshold intensity value is set to isolate the kidney stone region from the background.

8. **Region of Interest (ROI) Definition**: A polygonal region of interest (ROI) is defined around the suspected kidney stone area.

9. **Region Extraction**: The ROI is used as a mask to extract the kidney stone from the image.

10. **Analysis**: The extracted region is analyzed to determine if a kidney stone is detected based on its size and shape.

This project provides a comprehensive approach to kidney stone detection in ultrasonic images using MATLAB, facilitating accurate diagnosis and treatment planning.

---

