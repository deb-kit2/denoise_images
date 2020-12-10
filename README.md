# denoise_images
a few approaches to remove noise from old images

## 1. basic auto-encoder decoder with 3 layers to check feasibility
i.  image resolution needs to be readable enough, using (1000, 688), grayscale

result : yep, seems to work, quite readable.
todo : need to add layers, improve on quality of result image.

## 2. Median Filter
