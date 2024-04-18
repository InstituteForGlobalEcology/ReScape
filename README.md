# *ReScape*

## Section A: Introduction
![transform_4 17 23](https://github.com/InstituteForGlobalEcology/ReScape/assets/44954281/515ca862-fc81-4ab4-8a1e-58e749e676d1)

Since 1885, recreational photographers and scientists have been accumulating countless coral-reefscape images from around the world. However, the immense ecological information in these images have remained concealed because the images suffer from perspective distortion, which causes the size of organisms to decrease with increasing distance from the camera, rendering the images unusable for quantitative analysis of reef conditions. The *ReScape* algorithm solves this century-long problem by transforming coral-reefscape images into a top-down view, removing the perspective distortion and recovering the real size of organisms. The *ReScape* algorithm is available as a free, user-friendly App that does not require any coding experience. Our paper can be accessed here: https://doi.org/10.1038/s41598-024-59123-2

## Section B: How to download and run the *ReScape* App
Navigate to LINK and download the <ins>ReScape.exe</ins> file.

Windows users can readily run the *ReScape* App; Mac users must download and run the Windows operating system.

Note that the App takes 15–30 seconds to load upon startup. Please be patient for the introductory message to display.

## Section C: What you will need
1. A folder that contains the reefscape images to be transformed.
2. A folder for saving the transformed images.
3. A folder that contains camera-lens-calibration images. Refer to the <ins>camera_calibration.pdf</ins> file for instructions on how to capture these calibration images.

If you do not have any reefscape or calibration images yet and would like to practice using the *ReScape* App, examples of all the required files are included in the Tutorial folder.

## Section D: Image compatibility requirements
Your coral-reefscape images must have the following features to be transformable:
1. A relatively low to moderate rugosity area of a reef. Extremely variable changes in height (i.e., large crevices, steep slopes, anomalously tall colonies) do not respond well to the transformation.
2. The reef must vanish toward the background of the image, forming a horizon line where the reef vanishes into the water column. Therefore, the image cannot only be a reef; some water column must also be visible.
3. Good visibility. Avoid reefs with extremely high turbidity.

If colony sizes or the sampling area need to be determined, place at least one scale bar parallel to the reef plane.

To maximize the performance of *ReScape*, we strongly encourage you to read the Discussion section of our paper which explains these requirements in more detail and some more nuanced image-composition considerations.


## Section E: How to run *ReScape* with camera-lens calibration
1. Open the *ReScape* App.
2. Acknowledge the introductory message.
3. Select the folder where your reefscape images are stored.
4. Select the folder where you would like to save the transformed images.
5. Enter the percent of your CPU resources that you would like to use.
6. Indicate that you need to calibrate your camera.
7. Enter the name of your camera model.
8. Select the folder where you would like to save the camera-lens-calibration parameters.
9. Select the folder where your camera-lens-calibration images are stored.

## Section F: How to run *ReScape* with saved camera-lens-calibration parameters
1. Follow steps 1-5 in Section E.
2. Indicate that you have already calibrated your camera.
3. Select the appropriate camera-lens-calibration parameters file as detailed in the <ins>camera_calibration.pdf</ins> file.

## Section G: Additional Information
After processing is complete, you will have the option to process more images or exit the App. 

Camera-lens-calibration parameters are automatically saved to the folder selected in Section E Step 8. Therefore, each camera model only needs to be calibrated once. These parameters can be retrieved when transforming more images that were captured with the same camera that was previously calibrated. 

Consider organizing your survey images into different folders for each site and date (Section E Step 3). Then, process each folder separately and send their transformed images to separate folders (Section E Step 4). This approach will keep the transformed images organized in different folders for each unique survey.

If you plan on being away from your computer, consider entering a high value for CPU allocation to increase processing speed. If you are multitasking, consider entering a lower value to prevent *ReScape* from reducing the performance of your operating system and other Apps.

If you need to free up storage space, consider deleting the intermediate-image diagnostics after verifying that the images were accurately transformed.

Users who wish to modify the *ReScape* source code can navigate to LINK and download the <ins>ReScape.py</ins> file.

## Section H: Terms of Use and Attribution
Notably, the use of *ReScape* must attribute the authors, be noncommercial, and inherit the CC BY-NC-SA license in perpetuity if derivative work is created. Please refer to the <ins>LICENSE.txt</ins> file for *ReScape*’s complete Terms of Use. 

Please cite *ReScape* as follows:

Ferris, Z., Ribeiro, E., Nagata, T. & van Woesik, R. *ReScape*: transforming coral-reefscape images for quantitative analysis. *Sci. Rep.* <b>14,</b> 8915 (2024) https://doi.org/10.1038/s41598-024-59123-2










