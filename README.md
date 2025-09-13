### About the Project

### Model 1

This project basically outlines the implementation of a CNN architecture for a multi-class image classification problem. 
The employed CNN model highlights severely overfitted patterns. Hence, this project basically describes how to monitor overfitting and reduce the impact.


### Techniques used

* Python CNN
* Dropout layer Addition
* Data Augmentation
* Regularization  techniques
* Early stopping

### CNN Model Architecture

<img width="762" height="423" alt="image" src="https://github.com/user-attachments/assets/4ef8da96-9119-4027-885e-fbd0b1d6e91d" />


### Training and Validation Accuracy

Train loss: 0.0466
Train accuracy: 0.9994 

Test loss: 1.314
Test accuracy: 0.5612

<img width="536" height="470" alt="image" src="https://github.com/user-attachments/assets/f8b84234-b12a-42ea-bd64-1d1b0498da9f" />


The plots imply that the model is severely overfitted.

Hence, the following techniques are applied to reduce the impact. 

### Handling Overfitting - Data Augmentation

Train loss: 0.2833

Train accuracy: 0.9584 

Test loss: 0.9974

Test accuracy: 0.6393


A slight improvement in the model is visible as the training accuracy has slightly reduced and the testing accuracy has slightly increased from the previous step.

### Handling Overfitting - Early Stopping and Reducing Learning Rates

Train loss: 0.0835

Train accuracy: 0.9896 

Test loss: 1.1588

Test accuracy: 0.638

The overfitting problem remains in the problem. This is mainly due to the smaller dataset and the proposed CNN architecture that we are using for the problem.

### Model 2

This time, the CNN architecture is defined with some presteps to overcome overfitting. A new sufficient dataset is used for training for a multi-class classification problem. 


### Model Architecture

<img width="1178" height="750" alt="image" src="https://github.com/user-attachments/assets/6ad46cf0-639e-419b-8baf-eb196e3923e1" />

<img width="1037" height="427" alt="image" src="https://github.com/user-attachments/assets/832df5ca-2d0f-4092-b340-7306bb7250aa" />

Model Performace

<img width="637" height="482" alt="image" src="https://github.com/user-attachments/assets/fced8014-cf36-4c53-bf71-4b5fa1c96f94" />

With the application of Overfiiting preventing techniques, fair results are obtained for the model 2.






