RSNA Pneumonia Detection Challenge (Kaggle)
---------------------------------------------

This is a notebook about my simple experiment in RSNA Pneumonia Detection Challenge (`Kaggle <https://www.kaggle.com/c/rsna-pneumonia-detection-challenge>`_). This code is inspired by this `notebook <https://www.kaggle.com/jonnedtc/cnn-segmentation-connected-components>`_ , with some additional changes in the parameters. The objective of this challenge is to find the bounding boxes for predicted pneumonia cases, which is measured by mIoU (mean Intersection over Union). 

This notebook utilized ResNet (Residual Network) to find the segmentation map, and the 'activated' area would become the area of the bounding box. 