# Computer-Vision-2-image-inpainting

In this Notebook we will describe a class of *region filling algorithms* called **image inpainting**.

Imagine finding an old family photograph. You scan it and it looks great except for a few scratches.

# What is Image Inpainting?

Image inpainting is a class of algorithms in computer vision where the objective is to fill regions inside an image or a video.

The region is identified using a binary mask, and the filling is usually done by propagating information from the boundary of the region that needs to be filled.

The most common application of image inpainting is restoration of old scanned photos. It is also used for removing small unwanted objects in an image.
