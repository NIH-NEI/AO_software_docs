# Cone Segmentation ML

This tool performs segmentation of cone photoreceptors from non-confocal split detection.

## Usage and Features 
- Load an AO image by clicking on the **Open** button. Example AO images have been provided in the **test_data** folder in Github.
![Cone Detection Interface](images/ConeSegMLOpen2.png) 
- Click on the **Detect** button to automatically detect the cones.
![Cone Detection Interface](images/ConeSegMLSegment3.png) 
- The **Settings** tab provides options to display the centroids of the cones and also highlight the individual cone regions along with the contours.
![Cone Detection Interface](images/ConeSegMLSettings4.png) 
![Cone Detection Interface](images/ConeSegMLSettings5.png) 
- Click on **Save** button to save the annotations.
- The **Snapshot** feature allows users to save the current image with the applied annotations after selecting the desired output image size or scale.
![Cone Detection Interface](images/ConeSegMLSnapshot6.png) 
- Interactive refinement

    - The **Draw** button allows adding manual contours. The drawn contours can be made smoother (more round) by first checking **Smooth Annotations** in the Options tab and then continuously clicking the **Edit** button or the contour itself.
    - The **Erase S** button erases a single annotation.
    - The **Erase M** button erases multiple annotations.
    - The **Undo** button undoes the previous operation.
    - The **Edit** button allows modifying individual annotations and moving them to the desired location.
    - The **Adjust** option controls image brightness and contrast. After activating this feature, left-click and drag vertically to adjust brightness, and drag horizontally to adjust contrast.

