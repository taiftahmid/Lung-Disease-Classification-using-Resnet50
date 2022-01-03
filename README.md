# Lung Disease Classification using Resnet50

This repository is a classification model for detecting lung diseases from chest X-ray images. The dataset used for this project is given in the following [link](https://www.kaggle.com/nih-chest-xrays/data/kernels) .  

Some sample images from the dataset: 

![alt text](https://github.com/taiftahmid/Lung-Disease-Classification-using-Resnet50/blob/master/lung_disease_detection_image_sample.png)

Libraries used: Keras, pandas, matplotlib and sklearn. 

Image size used: 128x128. 

GPU used: TeslaK80 provided by Kaggle. 

Layers used in the Neural Network: 50 layers. 

Weights used: Imagenet.

Epochs: 1


# Results and Discussion: 

The following graph is the Area-Under-the-curve (AUC). 

![alt text](https://github.com/taiftahmid/Lung-Disease-Classification-using-Resnet50/blob/master/roc_curve.png)

From the graph it can be observed that the model can classify some diseases better than others. The accuracy can be further increased by using larger image sizes, increasing the number of layers, using hyperparameter tuning and training the model without using pre-trained weights through more number of epochs. 

Some visualizations of the results: 

![alt text](https://github.com/taiftahmid/Lung-Disease-Classification-using-Resnet50/blob/master/results.png)

This model is currently a work in progress. 




