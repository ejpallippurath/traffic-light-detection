# traffic-light-detection
The project aims to implement a red traffic light detection algorithm using computer vision techniques. The algorithm takes an input image and performs the following steps:

    1. Read the image using the OpenCV library.
    2. Convert the image from the BGR color space to the HSV color space.
    3. Define the upper thresholds for the red color in the HSV color space.
    4. Create a mask using the defined thresholds to identify pixels with red color.
    5. Apply the mask to the original image, extracting only the regions with red traffic lights.
    6. Display the resulting image, highlighting the detected red traffic lights.
    
 ![traffic_light_imshow](https://github.com/ejpallippurath/traffic-light-detection/assets/84701560/260e137e-6bad-4cc6-8f66-9b69c1075f67)
