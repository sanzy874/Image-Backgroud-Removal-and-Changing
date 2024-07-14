Image-Backgroud-Removal-and-Changing
Background was removed from images and new backgrounds were added.

-Why is it done?
Background removal allows isolation of objects.
Changing background helps in enhancement of visual appeal.
Customization and Personalization.
Creative Expression

-Libraries used?
1.   OpenCV (Open Source Computer Vision Library)(cv2):
It provides various functions for image and video processing, including reading, writing, resizing, filtering, etc
In this context, cv2 is used for resizing images (cv2.resize()) and blending images (cv2.addWeighted())

2.   scikit-image (skimage): 
It provides various functions and algorithms for image processing tasks such as reading and writing images, image filtering, segmentation, and feature extraction.
In this code, skimage.io.imread() is used to read images from files.

3. Matplotlib:
It provides functions for plotting and displaying images, graphs, charts, and other visualizations.
In this code, matplotlib.pyplot.imshow() is used to display images.

4.   rembg: 
It provides a simple interface for removing backgrounds from images while preserving the foreground objects.  
    In this code, rembg.remove() is used to remove the background from input images.

5. numpy:
     It provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays.
     In this code, numpy is used for various array manipulation tasks, such as stacking arrays (np.dstack()) and creating arrays filled with specific values (np.ones()).

-Real Life Applications?
Product photography for E-commerce
Graphic design and advertising
Studio photography
Forensic and Scientific analysis

-Limitations?
Algorithms may struggle with complex backgrounds
Fine details and edges may be removed which may result in loss of details.
Hard to achieve proper blend of the images even after changing the alpha value





