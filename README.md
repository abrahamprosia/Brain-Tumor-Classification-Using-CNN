# Brain MRI Classification

## Overview
In this project, I developed a model to classify brain MRI images into four categories: Pituitary tumor, Glioma tumor, Meningioma tumor, and No tumor.

## Methods
- I used TensorFlow to build a Convolutional Neural Network (CNN) for image classification.
- Data augmentation was applied to increase the diversity of the training dataset by introducing variations to the images, such as rotation, flipping, and scaling.

## Results
- The model achieved a test accuracy of 94%.
- The test loss was measured at 1.02.
  
### Performance Metrics
The model demonstrated strong performance on both training and validation datasets.  

#### Training Data:
- **Accuracy**: 99%  
- **Precision**: 0.99  
- **Recall**: 0.99  
- **F1-Score**: 0.99  

| Class        | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| Glioma       | 1.00      | 0.99   | 0.99     | 1061    |
| Meningioma   | 0.98      | 1.00   | 0.99     | 1072    |
| No Tumor     | 1.00      | 0.99   | 0.99     | 1288    |
| Pituitary    | 1.00      | 1.00   | 1.00     | 1149    |

#### Validation Data:
- **Accuracy**: 94%  
- **Precision**: 0.94  
- **Recall**: 0.94  
- **F1-Score**: 0.94  

| Class        | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| Glioma       | 0.93      | 0.93   | 0.93     | 260     |
| Meningioma   | 0.89      | 0.90   | 0.89     | 267     |
| No Tumor     | 0.98      | 0.93   | 0.95     | 307     |
| Pituitary    | 0.96      | 0.99   | 0.97     | 308     |

### Test Set Performance
- **Accuracy**: 94%  
- **Loss**: 1.02  

## Additional Information
For a detailed walkthrough of the code and the complete results, please refer to the accompanying Jupyter Notebook file.  










