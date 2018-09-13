# udacity-ml-capstone

## Introduction

For my Udacity Machine Learning Capstone project I chose to implement a Landmarks classifier that predicts the label of the input image.


## Reports

- report.pdf
- proposal.pdf

## Code

- basic CNN.ipynb : has the benchmark model code

- transfer learning.ipynb : has the transfer learning of pretrained models, models after refiniement and senstivity analysis

- Upload dataset.ipynb : code to  upload dataset from google drive to google colabatory

- test.ipynb : code to upload solution model from google drive to google colabatory and its 
predictions

Note that the code is runned on google colabatory not locally on jupyter notebook 

## Input files

- Dataset that I used is in this link (https://landmark3d.codeplex.com/)
- Models folder has three .json files 
	1)Basic_CNN.json for benchmark model
	2)VGG16_model.json for VGG16 model
        3)InceptionV3_model.json for InceptionV3 model

and six .h5 files has the weights of the model used
	- InceptionV3_before.h5 , InceptionV3_after.h5 ,InceptionV3_robust.h5 for Inception model before refinement, after refinement and after 	senstivity analysis.
	- VGG16_before.h5 , VGG16_after.h5 for VGG16 model before refinement and after refinement.

- Note that the solution model weights is InceptionV3_after.h5

## Technologies used

- [Python 3.x](https://www.python.org)
- [Tensorflow](https://www.tensorflow.org)
- [Keras](https://keras.io)






