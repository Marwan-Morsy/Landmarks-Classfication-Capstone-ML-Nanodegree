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

- The full project is in this link (https://drive.google.com/drive/folders/1ybn-2C3KCyW1jnV2MfPurNtvjsZsdy5C?usp=sharing)

It has 4 folders which are

- Dataset folder has three .zip files 1)train.zip  2)test1.zip 3)validation.zip for training, testing and validation respectively.

- Models folder has three .json files 
	1)Basic_CNN.json for benchmark model
	2)VGG16_model.json for VGG16 model
        3)InceptionV3_model.json for InceptionV3 model

and six .h5 files has the weights of the model used
	- basic_cnn.h5 for benchmark model
	- InceptionV3_before.h5 , InceptionV3_after.h5 ,InceptionV3_robust.h5 for Inception model before refinement, after refinement and after 	senstivity analysis.
	- VGG16_before.h5 , VGG16_after.h5 for VGG16 model before refinement and after refinement.

- Note that the solution model weights is InceptionV3_after.h5

- Bottleneck features folder that has 9 .npy files
  VGG16 model has 3 files for training, validation and testing.
  InceptionV3 model has 3 files on the used dataset and
 the other 3 files on modified dataset after sensentivity analysis which will lead to the InceptionV3_robust.h5 weights.





