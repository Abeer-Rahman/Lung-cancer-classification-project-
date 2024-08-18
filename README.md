# Lung-cancer-classification-project-
The goal of this project is to classify lung cancer images. The dataset comprises CT scans of four types of lungs: Adenocarcinoma, Large cell carcinoma, Normal, and Squamous cell carcinoma.
A pretrained convolutional base Vgg19 was used to pull out the features from the images. Squeeze excitation block has been integrated with the the Residual block, and was incorporated into the last two output layers of the pre-trained vgg19 convolutional base.
Since we only had 613 training images, we applied data augmentation techniques to enhance the dataset. The model achieved an accuracy of 93% on the test data. Finally, the entire process was implemented using Gradio software.
Dataset:https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
