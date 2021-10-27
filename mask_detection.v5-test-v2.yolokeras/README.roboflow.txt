
mask_detection - v5 Test-V2
==============================

This dataset was exported via roboflow.ai on October 27, 2021 at 9:40 PM GMT

It includes 325 images.
Masks are annotated in YOLO v3 (Keras) format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -15 and +15 degrees

The following transformations were applied to the bounding boxes of each image:
* 50% probability of horizontal flip


