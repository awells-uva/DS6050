
mask_detection - v12 faster R-CNN
==============================

This dataset was exported via roboflow.ai on November 7, 2021 at 6:41 PM GMT

It includes 666 images.
Masks are annotated in Tensorflow TFRecord (raccoon) format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -15 and +15 degrees
* Random brigthness adjustment of between -25 and +25 percent
* Random exposure adjustment of between -20 and +20 percent


