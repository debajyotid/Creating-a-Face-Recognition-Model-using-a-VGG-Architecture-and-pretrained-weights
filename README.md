### Face Recognition
In this hands-on project, the goal is to build a face identification model to recognize faces. 
The model uses Aligned Face Dataset from Pinterest. This dataset contains 10770 images for 100 people. All images are taken from 'Pinterest' and aligned using dlib library.

## Overview
In this problem, we use a pre-trained model trained on Face recognition to recognize similar faces.
Here, we are particularly interested in recognizing whether two given faces are of the same person or not. Below are the steps performed in the project.

● Load the dataset and create the metadata.

● Check some samples of metadata.

● Load the pre-trained model and weights.

● Generate Embedding vectors for each face in the dataset.

● Build distance metrics for identifying the distance between two given images.

● Use PCA for dimensionality reduction.

● Build an SVM classifier to map each image to its right person.

● Predict using the SVM model.

#### Skills and Tools
Face Recognition, VGG,SVM,Embeddings,Similarity Distance,OpenCV,PCA,StandardScaler,LabelEncoder
