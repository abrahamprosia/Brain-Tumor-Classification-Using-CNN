# Brain MRI Classification

## Overview
In this project, I developed a model to classify brain MRI images into four categories: Pituitary tumor, Glioma tumor, Meningioma tumor, and No tumor.

## Methods
- I used TensorFlow to build a Convolutional Neural Network (CNN) for image classification.
- Data augmentation was applied to increase the diversity of the training dataset by introducing variations to the images, such as rotation, flipping, and scaling.

## Results
- The model achieved a test accuracy of 94%.
- The test loss was measured at 1.02.
- 
Classification Report for Training Data:
              precision    recall  f1-score   support

      glioma       1.00      0.99      0.99      1061
  meningioma       0.98      1.00      0.99      1072
     notumor       1.00      0.99      0.99      1288
   pituitary       1.00      1.00      1.00      1149

    accuracy                           0.99      4570
   macro avg       0.99      0.99      0.99      4570
weighted avg       0.99      0.99      0.99      4570


Classification Report for Validation Data:
              precision    recall  f1-score   support

      glioma       0.93      0.93      0.93       260
  meningioma       0.89      0.90      0.89       267
     notumor       0.98      0.93      0.95       307
   pituitary       0.96      0.99      0.97       308

    accuracy                           0.94      1142
   macro avg       0.94      0.94      0.94      1142
weighted avg       0.94      0.94      0.94      1142


# To see more detailed result please see the other file which include my codes and results in jupyter notebook









