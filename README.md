# Behavioural Context Recognition from Mobile Sensors

Behavioral Context refers to a wide range of attributes describing what is going on with the user like: where the user is (at home, at work), what the user is doing (sleeping, eating, in a meeting, exercising), who the user is with (family, friends, co-workers), user’s body posture state (sitting, standing, walking, running), and so on. In this project, we analyzed data obtained from various sensors present in smartphones and smartwatches, and found how a unique combination of these data points can be used to identify a user uniquely. To facilitate our project, we made use of the 'Extrasensory' dataset and performed the task of behavioral context recognition by using Machine Learning algorithms like Logistic Regression, K-Nearest Neighbors, Random Forest, K-means Clustering, Gaussian Mixture Model, Dimensionality reduction using Principal Component Analysis, Artificial Neural Network and Multiclass classification using Multilayer Perceptron.

## Experiments Performed for Behavioural Context Recognition:

- Activity detection (walking) based on features - phone accelerometer and smartwatch accelerometer, using Logistic Regression, K-Nearest Neighbors, Random Forest
- Activity detection (walking) based on features - phone accelerometer, watch accelerometer, gyroscope and location sensor, using Logistic Regression, K-Nearest Neighbors, Random Forest
- Activity detection (walking) based on features - location sensor and audio, using Logistic Regression, K-Nearest Neighbors, Random Forest
- Clustering data based on every feature, i.e sensor available using K-Means Clustering
- Clustering data based on all features, using GMM
- Dimensionality reduction using PCA and checking for prediction accuracy
- Clustering data based on accelerometer and gyroscope features only (using K-means clustering and GMM)
- Activity Recognition of user based on sensor data from phone accelerometer and watch accelerometer by performing multiclass classiﬁcation using Multilayer Perceptron
- Activity Recognition of user based on sensor data from phone accelerometer and watch accelerometer, gyroscope and location data by performing multiclass classiﬁcation using Multilayer Perceptron
- Activity Recognition of user based on sensor data from phone’s location data and audio data at certain timestamps, by performing multiclass classiﬁcation using Multilayer Perceptron
- Making use of an Artiﬁcial Neural Network to perform binary classiﬁcation of any activity of a user - walking in this instance using smartphone accelerometer and watch accelerometer
- Binary classiﬁcation using ANN, performing binary classiﬁcation of user activity based on gyroscope data, location and audio features

## Dataset

The Dataset used for this project is the Extrasensory dataset (http://extrasensory.ucsd.edu/), which is a publicly available dataset that was obtained by collecting smartphone and smartwatch sensor data available from around 60 iPhone users, over a period of 7 days by collecting data at every single minute. This included the following sensor data: accelerometer, gyroscope, magnetometer, audio, location, and phone-state etc. There are 51 different context label columns in the dataset. The class labels are Physical Activities (e.g., walking, running), Daily Activities (e.g., sleeping) , Locations (e.g., school, work, home) etc.

## How to run the implementation of this project?

Make use of the **MPC_Project.ipynb** file for this purpose. Host this file on Google Colab, and run the entire code. 
