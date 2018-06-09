# Image Classification with Cifar-10 dataset

## Source: [Alex Krizhevsky's home page](https://www.cs.toronto.edu/~kriz/cifar.html)

## Dataset Download: 
* [Data Folder](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz), 
* [Data Set Description](https://www.cs.toronto.edu/~kriz/cifar.html)

## Abstract: 
* The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. * There are 50000 training images and 10000 test images. 
* The dataset is divided into five training batches and one test batch, each with 10000 images. 
* The test batch contains exactly 1000 randomly-selected images from each class. 
* The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 

* These are the classes in the dataset:
1. airplane										
2. automobile										
3. bird										
4. cat										
5. deer										
6. dog										
7. frog										
8. horse										
9. ship										
10. truck										

* The classes are completely mutually exclusive. 
i.e. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.


## Approach
* Imported dataset
* Analysed data
* Applied PCA
* Prediction using Random Forest 
* Prediction using KNN 
* Prediction using Logistic Regression 
* Prediction using SVM 
* Comparison between various classifier

## Results
* RandomForestClassifier :  0.287
* K Nearest Neighbors :  0.2284
* Logistic Regression :  0.4076
* Support Vector Classifier :  0.5522

## Conclusion
Best accuracy comes from Support vector classifier. Although, It can be further improved by using neural networks (which i will be deploying in other repository.)

## Clone the Project:
```git clone https://github.com/wikiabhi/Cifar-10.git```


``` MIT License ```
```Copyright (c) 2018 Abhishek```