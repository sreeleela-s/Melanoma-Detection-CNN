# Melanoma Detection
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
	The data set contains the following diseases:

	1. Actinic keratosis
	2. Basal cell carcinoma
	3. Dermatofibroma
	4. Melanoma
	5. Nevus
	6. Pigmented benign keratosis
	7. Seborrheic keratosis
	8. Squamous cell carcinoma
	7. Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
 1. If we obesrve the text above the images after applying the model on test data, we can see that that actual and the predicted values are correct.
     Model is able to predict well. 
	 Eg: Image-1 the Actual value is dermatofibroma and the Predicted value is also dermatofibroma

 2. Model Accuracy:

	Validation Accuracy: 80%

	Traning Accuracy: 93%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
	import pathlib
	import tensorflow as tf
	import matplotlib.pyplot as plt
	import numpy as np
	import pandas as pd
	import os
	import PIL
	from tensorflow import keras
	from tensorflow.keras import layers
	from tensorflow.keras.models import Sequential
	from glob import glob
	from tensorflow.keras.layers.experimental.preprocessing import Rescaling
	from tensorflow.keras.layers import Dense, Dropout, Activation, Flatten, BatchNormalization, Conv2D, MaxPooling2D
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Appreciate the course content by Upgrad and IIIT Bangalore , helping me analyse this data


## Contact
Created by [@sreeleela-s] - feel free to contact me!

