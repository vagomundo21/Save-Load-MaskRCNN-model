# Save-Load-MaskRCNN-model
## This is an attempt at solving the issue with saving and loading MaskRCNN model.

- For saving model after training, view [save_maskrcnn.ipynb](save_maskrcnn.ipynb) file.
- If the model architecture is changed, change it simultaneously in 2nd block of 'save_maskrcnn.ipynb' which is a modified version of [model.py](https://github.com/matterport/Mask_RCNN/blob/master/mrcnn/model.py) from [MaskRCNN](https://github.com/matterport/Mask_RCNN/blob/master/mrcnn/) by matterport.
- The changes are just related to code and not the architectural. The model architecture in [model.py](https://github.com/matterport/Mask_RCNN/blob/master/mrcnn/model.py) and [save_load_maskrcnn.ipynb](save_load_maskrcnn.ipynb) is same.
- After reviewing the model, save the model entirely or in JSON file.
- While loading JSON file or the H5 file, refer [load_maskrcnn.ipynb](load_maskrcnn.ipynb) file. Whenever the model is to be loaded, code in [load_maskrcnn.ipynb](load_maskrcnn.ipynb) should be executed first.
- **Remember that [save_maskrcnn.ipynb](save_maskrcnn.ipynb) and [load_maskrcnn.ipynb](load_maskrcnn.ipynb) shouldn't be executed simultaneously.**
