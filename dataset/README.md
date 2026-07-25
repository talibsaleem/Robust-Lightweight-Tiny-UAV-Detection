# YOLO-based Segmented Dataset for Drone Detection

Unmanned aerial vehicles (UAVs) have become increasingly popular in recent years for both commercial and recreational purposes. Regrettably, the security of people and infrastructure is also clearly threatened by this increased demand. To address the current security challenge, much research has been carried out and several innovations have been made. Many faults still exist, however, including type or range detection failures and the mistaken identification of other airborne objects (for example, birds). A standard dataset that contains photos of drones on which the model might be trained for greater accuracy is needed in order to conduct experiments in this field. The supplied dataset is crucial since it will help train the model, giving it the ability to learn more accurately and make better decisions. The dataset that is being presented is comprised of a diverse range of images of drones in motion. Pexel's website's images and videos have been used to construct the dataset. Images were obtained from the frames of the recordings that were acquired, after which they were segmented and augmented with a range of circumstances. All bird samples have been removed; the dataset now contains only drones. The dataset has been formatted according to the YOLOv7 PyTorch specification. The test, transit, and valid folders are contained within the given dataset. These folders each feature a plaintext file that corresponds to an associated image. Relevant metadata regarding the discovered object is described in the plaintext file. Images and labels are the two subfolders that constitute the folders. The images have a 640 x 640 pixel resolution and are stored in JPEG format.

## Test
This folder has two subfolders: `images` and `labels`. The `images` folder now contains only drone images, and labels map to drone instances.

## Train
This folder has two subfolders: `images` and `labels`. The `images` folder now contains only drone images, and labels map to drone instances.

## Valid
This folder has two subfolders: `images` and `labels`. The `images` folder now contains only drone images, and labels map to drone instances.
