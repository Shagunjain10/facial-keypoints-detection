# facial-keypoints-detection

## Dataset link
https://www.kaggle.com/c/facial-keypoints-detection/data

## Description
In facenet_model.ipynb
I predict the facial keypoints of face. 
In the dataset initially 2140 non-null values. After the data augmentation using numpy and opencv the dataset convert to 8560 non-null values.
For training the model I use ResNet. In ResNet model, I created a Res Block and Identity block.
The accuracy on test dataset is 77.69%.
