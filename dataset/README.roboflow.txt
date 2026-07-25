
Drone Dataset - v3 2022-12-22 1:29am
==============================

This drone-only dataset was exported via roboflow.com on December 21, 2022 at 9:03 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

All bird images have been removed; the set now includes only drone images annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -34 and +34 degrees
* Random shear of between -21° to +21° horizontally and -29° to +29° vertically
* Random brigthness adjustment of between -38 and +38 percent
* Random exposure adjustment of between -28 and +28 percent
* Random Gaussian blur of between 0 and 5.5 pixels
* Salt and pepper noise was applied to 1 percent of pixels


