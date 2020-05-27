# Global-Wheat-Detection
 Kaggle Object detection
 Only one class (wheat) is required to be detected

First notebook: EDA
-----------------------------------------------------------
1) EDA
2) Visualizing images

Second notebook: modeling using keras-retinanet
-----------------------------------------------------------
1) Installing Keras-RetinaNet
2) Preprocessing Data for Input to RetinaNet
   * didn't use the whole training set for training
3) Preparing Files to be given for training (Annotation file, Class file)
4) Downloading the pretrained model
5) Training Model
   * batch size is limited to 1 because of the limited gpu resources (GTX 1060 6G)
   * step = 100 in order to save time
6) Loading the trained model
7) Display prediction
8) Submission

Conclusion:
-----------------------------------------------------------
The model accuracy of this notebook was not good. Only one testing image out of 10 can be detected wheat. Need more powerful gpu for training.
