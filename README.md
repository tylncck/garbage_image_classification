# Garbage Image Classification
In this project the aim is to create a model and an application to help people correctly sort the garbage items and use the correct bins. This is not only a learning project but also a contribution to a more environmentally sustainable world.

Our model will classify garbage items as: Trash, Compost or Recycling. We have implemented this model in a variety of ways, including a web application and even a trash sorting robot! 

## 1. Model: 
The image classification model is a convolutional neural network built with Tensorflow. It consists of an input layer, 9 convolutional 2D layers, 4 Max Pooling 2D layers, 1 flatten layer, and 3 Dense layers. The model was trained on data from [Kaggle](https://www.kaggle.com/datasets/mostafaabla/garbage-classification?select=garbage_classification). However, based on our real life testing, we have manually added garbage photos to eliminate misclassification patterns. (Credits: Taylan Cicek)

## 2. Web Application
The application was built on a Dash framework. Then, we built a Docker container with all the app dependencies. Finally, the docker was deployed to Google Cloud Run. (Credits: Ibtassam Rasheed and José Palacios)