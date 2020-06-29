# COVID-19 Chest X-Ray Image Classification

![preview](https://github.com/KongpolC/COVID-19_Image_Classification/blob/master/images/preview.png)

Apply transfer learning from ResNet50 v.2 with weights from ImageNet to classify chest X-ray images into 3 classes which are

``` classes
0: COVID-19 infected
1: Normal
2: Pneumonia from causes other than COVID-19
```

Trained on 3,641 images and validated on 473 images.
![training_graph](https://github.com/KongpolC/COVID-19_Image_Classification/blob/master/images/training_graph.jpg)

## Result

![confusion_matrix](https://github.com/KongpolC/COVID-19_Image_Classification/blob/master/images/confusion_matrix.png)

``` metrics
              precision    recall  f1-score   support

       covid       0.96      0.95      0.96        80
      normal       0.95      0.90      0.93       235
   pneumonia       0.86      0.93      0.89       158

    accuracy                           0.92       473
   macro avg       0.92      0.93      0.93       473
weighted avg       0.92      0.92      0.92       473

Average F1-Score = 0.9251186853945429
```
