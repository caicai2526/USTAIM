# USTAIM
We release the code. Please install the corresponding dependency packages
## Create patches
First, you need to create patches for whole slide images.  We conducted secondary development based on deepzoom_tile in Openslide 4.6.0.66 and cropped images at the specified level in WSI into image blocks. You can run tile_WSI.py in the create_patch.
## Code run
You need to use the normalization method to normalize the patches. We used the Vahadane color standardization method for processing. After that, you can try to run the process from step 1 to step 6.
