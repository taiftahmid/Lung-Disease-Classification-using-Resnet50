# Lung-Disease-Classification-using-Resnet50

This repository is a classification model for detecting lung diseases from chest X-ray images. The dataset used for this project is given in the following [link](https://www.kaggle.com/nih-chest-xrays/data/kernels) .  

Some sample images from the dataset: 

![alt text](https://www.kaggleusercontent.com/kf/8342432/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..PmbtUmKyuOMyUcSX-1oVKA.fP0PCmi8Iew-0fahI6RH_t3R-gUmWpfgCDov9AuJbW3C7NrGPH0phufy2Wxjk8UvzgfvXdpnh4UNgcGENAut-UfaQi8_C6fDdwdr-sm4_2Xh2VxNGNvTiLrSyx5Qh1OIZbiS4ouiYBgCFZG3TBvGLchHx5pwLj3Iu24flpnIIr1RzTXH4WMakWKhahHZTz6p.yfeuDDIgBRdjrYGYjhnD5A/__results___files/__results___12_0.png)

Libraries used: Keras, pandas, matplotlib and sklearn. 

Image size used: 128x128. 

GPU used: TeslaK80 provided by Kaggle. 

Layers used in the Neural Network: 50 layers. 

Weights used: Imagenet.

Epochs: 1


# Results and Discussion: 

The following graph is the Area-Under-the-curve (AUC). 

![alt text](https://www.kaggleusercontent.com/kf/8342432/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..PmbtUmKyuOMyUcSX-1oVKA.fP0PCmi8Iew-0fahI6RH_t3R-gUmWpfgCDov9AuJbW3C7NrGPH0phufy2Wxjk8UvzgfvXdpnh4UNgcGENAut-UfaQi8_C6fDdwdr-sm4_2Xh2VxNGNvTiLrSyx5Qh1OIZbiS4ouiYBgCFZG3TBvGLchHx5pwLj3Iu24flpnIIr1RzTXH4WMakWKhahHZTz6p.yfeuDDIgBRdjrYGYjhnD5A/__results___files/__results___19_0.png)

From the graph it can be observed that the model can classify some diseases better than others. The accuracy can be further increased by using larger image sizes, increasing the number of layers, using hyperparameter tuning and training the model without using pre-trained weights through more number of epochs. 

Some visualizations of the results: 

![alt text](https://www.kaggleusercontent.com/kf/8342432/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..PmbtUmKyuOMyUcSX-1oVKA.fP0PCmi8Iew-0fahI6RH_t3R-gUmWpfgCDov9AuJbW3C7NrGPH0phufy2Wxjk8UvzgfvXdpnh4UNgcGENAut-UfaQi8_C6fDdwdr-sm4_2Xh2VxNGNvTiLrSyx5Qh1OIZbiS4ouiYBgCFZG3TBvGLchHx5pwLj3Iu24flpnIIr1RzTXH4WMakWKhahHZTz6p.yfeuDDIgBRdjrYGYjhnD5A/__results___files/__results___20_0.png)

This model is currently a work in progress. 




