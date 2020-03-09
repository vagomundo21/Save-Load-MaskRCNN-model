# Save-Load-MaskRCNN-model
This is an attempt at solving the issue with saving and loading MaskRCNN model.

For saving and loading model, view [save_load_maskrcnn.ipynb](save_load_maskrcnn.ipynb) file.
If the model architecture is changed, change it simultaneously in 2nd block of 'save_load_maskrcnn.ipynb' which is a modified version of [model.py](https://github.com/matterport/Mask_RCNN/blob/master/mrcnn/model.py) from [MaskRCNN](https://github.com/matterport/Mask_RCNN/blob/master/mrcnn/) by matterport.
After reviewing the model, save the model entirely or in JSON file.
While loading JSON file or the H5 file, give proper custom objects and while doing so, the first two blocks of [save_load_maskrcnn.ipynb](save_load_maskrcnn.ipynb) file must be executed prior.
