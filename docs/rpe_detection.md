# RPE Detection

This tool detects retinal pigment epithelial (RPE) cells from AO enhanced indocyanine green (AO-ICG) images.

## Usage and Features 
- Load an AO image by clicking on the **Open** button. Example AO images have been provided in the **test_data** folder in Github.
![Cone Detection Interface](images/RPEDetectOpen2.png) 
- Click on the **Detect** button to automatically detect the cones.
![Cone Detection Interface](images/RPEDetectbutton3.png) 
- The **Settings** tab provides options to display the centroids of the cones and also highlight the individual cone regions along with the contours.
![Cone Detection Interface](images/RPEDetectDisplaySetting4.png) 
![Cone Detection Interface](images/RPEDetectVoronoi5.png) 
- Click on **Save** button to save the annotations.
- The **Snapshot** feature allows users to save the current image with the applied annotations after selecting the desired output image size or scale.
![Cone Detection Interface](images/RPEDetectionSnapshot6.png) 
- Interactive refinement

    - The **Add** button allows adding annotations.
    - The **Erase S** button erases a single annotation.
    - The **Erase M** button erases multiple annotations.
    - The **Undo** button undoes the previous operation.
    - The **Move** button moves individual annotations to the desired location.
    - The **Adjust** option controls image brightness and contrast. After activating this feature, left-click and drag vertically to adjust brightness, and drag horizontally to adjust contrast.