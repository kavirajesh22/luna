# Luna
Luna: An Intelligent Satellite Health-Monitoring Framework. Synopsys Science Fair Project 2022

lunaofficialcnn.ipynb: contains code to the Convolutional Neural Network.
lunaofficialsciml.ipynb: contains code to K-Nearest Neighbors, MultiLayer Perceptron, and Support Vector Machines.


Abstract:
Satellites are known as remotely operated systems that carry a high degree of complexity,
and their photos are widely used amongst various fields, especially in identifying and tracking
human and natural activity. By checking the quality of its photos and identifying any possible
anomalies, the health of a satellite can be effectively monitored. The goal of Luna as a
framework is to verify the quality of raw satellite images produced and check for anomalies that
may be present in satellite images, contributing to the long-term task of monitoring satellite
health and guaranteeing better image quality. 160 “unhealthy” and “healthy” photos were
gathered from NASA satellites Landsat 7 (2003), Landsat 4 (2022), and Sentinel (2022). These
images made up the training and validation dataset that was used to power four different Python
Machine Learning models: Convolutional Neural Networks, K-Nearest Neighbors, MultiLayer
Perceptron, and Support Vector Machines. Two trials, one with 80 images as the dataset and the
second with 160 images, were conducted. KNN had the total highest accuracy of the validation
dataset with 77%, and CNN had the second highest with 62%. The simplicity of KNN has made
it efficient in solving this problem- it assumes that similar data are near each other, and linearly
separates the data that is presented. While CNN was expected to achieve the highest accuracy
because of its reliability, the algorithm needs more training data in order to be more successful.
With Luna, image quality can become better guaranteed, especially in the field of satellite data.
By investigating this problem, image classification can become stronger, and this work provides
a strong foundation to improving image quality in various like problems.
