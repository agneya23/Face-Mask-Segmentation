# Face Mask Segmentation

Segmentation is performed on a Face Mask Dataset. The segmentation masks highlight the location of a face mask on a person's face. Aim is to highlight the Face Masks on the test images. Face Detection is first performed using HaarCascades in OpenCV post which the DeepLabV3_resnet50 pre-trained segmentation model is fine-tuned on the pre-processed training set. IOU of 0.78 is achieved on the extracted test set. 

The dataset was obtained from Kaggle: https://www.kaggle.com/datasets/perke986/face-mask-segmentation-dataset
