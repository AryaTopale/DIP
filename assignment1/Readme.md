# Image Processing and Video Manipulation Report

## Introduction
This report provides an overview of various image processing techniques and video manipulation tasks implemented using OpenCV and Python. The tasks cover a range of operations from basic image reading and writing to more advanced techniques like brightness adjustment, contrast enhancement, and video frame manipulation. Each task is accompanied by visual examples to demonstrate the results.

## Task 1: Reading and Displaying an Image
The first task involves reading an image from disk, converting its color space from BGR (used by OpenCV) to RGB (used by Matplotlib), and displaying it. This step is fundamental to many image processing pipelines.

![Original Image](../media/images/obito.png)

## Task 2: Writing an Image to Disk
In this task, the image read in Task 1 is saved to disk. This is crucial for storing processed images after modifications.

## Task 3: Changing the Brightness of an Image
Brightness adjustment is a common image processing operation. In this task, the brightness of an image is increased by a fixed value, resulting in a brighter image.

**Original Image**  
![Original Image](../media/images/obito.png)

**Brightness Adjusted Image**  
![Brightness Adjusted Image](../media/images/output/Q3.png)

## Task 4: Enhancing Image Contrast
This task involves enhancing the contrast of a low-contrast image using a combination of gamma correction and unsharp masking. The resulting image shows improved contrast, making details more visible.

**Original Image**  
![Low Contrast Image](../media/images/lowcontrast.png)

**Enhanced Image**  
![Enhanced Image](../media/images/output/Q4_enhanced.png)

## Task 5: Converting an Image to Grayscale
Converting a color image to grayscale is a foundational task in image processing. The grayscale image is created by averaging the color channels, resulting in an image where intensity represents brightness.

**Original Image**  
![Original Image](../media/images/spiderman.png)

**Grayscale Image**  
![Grayscale Image](../media/images/output/Q5.png)

## Task 6: Converting a Grayscale Image to RGB
Pseudo-color mapping is applied to a grayscale image to convert it back to a color image. This technique can be useful for visualizing different intensity levels in the grayscale image.

**Original Image**  
![Grayscale Image](../media/images/output/Q5.png)

**Pseudo-colored Image**  
![Pseudo-colored Image](../media/images/output/Q6.png)

## Task 7: Green Screen Replacement
In this task, a green screen image is replaced with a background image. The green pixels are detected and replaced with corresponding pixels from the background, creating a composite image.

![Green Screen](../media/images/greenscreen.png)

![Background](../media/images/background.png)
![Green Screen Replacement](../media/images/output/Q7.png)
## Task 8: Reading a Video File and Converting to Frames
A video file is read and converted into an array of frames. This is a common preprocessing step in video analysis tasks where each frame needs to be processed individually.

## Task 9: Creating a Transition Video
A smooth transition between two images is created by blending them over a series of frames. The result is a video where the first image gradually transitions into the second, creating a fade effect.

<a href='https://iiitaphyd-my.sharepoint.com/:v:/g/personal/arya_topale_students_iiit_ac_in/EZktnwlm8UJFjfSxQlCJ_WsBqZiaoJrtQ2ZU6V_9BbiiPQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=HgYvhH'>Transition Video</a>

## Conclusion
This report showcases various image processing and video manipulation techniques using OpenCV. These tasks provide a foundation for more complex image and video analysis applications. Each technique is demonstrated with visual examples to illustrate the effects of the operations.