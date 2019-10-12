
# Mask_RCNN_Multiclass_CustomData

Mask R-CNN trained on Custom Multi-Class data using pre-trained coco weights. 


## Getting Started

This model is trained using Google Colab to show the example for custom data training and testing.

### Prerequisites

1. Need data and divide it into train and val folders inside the dataset folder
2. Install Annotate VGG Annotation tool  http://www.robots.ox.ac.uk/~vgg/software/via/
3. Annotate each train and val folder
4. Place each json file generated into their respective train and val folder
5. A Google account is needed to use Google colab https://colab.research.google.com/notebooks/welcome.ipynb
6. Upload the whole folder on Google drive
7. Use the utensils_train_n_inspection.ipynb file to train and validate your model
8. Weights will be placed inside Mask_RCNN-master/logs/ folder


This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* https://github.com/matterport/Mask_RCNN
* https://engineering.matterport.com/splash-of-color-instance-segmentation-with-mask-r-cnn-and-tensorflow-7c761e238b46
