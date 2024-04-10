# Ground-Based-Cloud-Classification

### Dataset: 
[Ground Based Cloud Dataset (GBCD)](https://github.com/Pulpy-y/Ground-Based-Cloud-Dataset)

## File descriptions:
1. Best_model.ipynb: This file helps to visualize the performance of the best classification model. There is a need to change the path to the dataset and model file. Best model can be downloaded [here]( https://drive.google.com/file/d/1YDrlkTc5jv4zt8GY_TRQY1f2W57iAo_x/view?usp=sharing)
2. Classification with CCSN + preprocessing.ipynb: Initial implementation and experiment with [CCSN dataset](https://github.com/upuil/CCSN-Database), with a few pre-processing steps such as mean value subtraction.
3. Cloud Classification Training.ipynb: File for training the classification models with different parameters, such as the addition of batch normalization. Trained with GBCD dataset.
4. Dataset Preprocessing.ipynb: A few functions for preprocessing, such as code to generate augmented images and calculate mean values. There are more functions for pre-processing but not included in the file yet.
5. Motion tracking.ipynb: Code to use the model trained to classify a region selected from video, and calculate wind speed based on it. Videos should be processed into frames first.

### Contact
For any questions on the code, contact via email yaoyi2000326@gmail.com


   
