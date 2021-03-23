# denoise_images
a few approaches to remove noise from old images

## 1. basic auto-encoder decoder with 3 layers to check feasibility.
Simple enough to do the job. Not good with lines.<br>Also, not bright enough. Can be fixed by thresholding.

## 2. Median Filter
Scipy's median filter in use, varied background thresholds and kernel sizes.
