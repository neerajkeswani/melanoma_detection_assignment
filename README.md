# melanoma_detection_assignment
> o build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis


## Conclusions
- Cafter 20 epochs training accuracy gets over 92% where as validation stays arround 50%, which is clear sign of overfitting. Same can be seen in loss.
- Seborrheic Keratosis class has the least number of samples 
- Pigmented Benign Keratosis classes dominate the data in terms proportionate number of samples
- There as been a significant increase in accuracy using augmentor library. We can perform better by using more CNN units and HP tuning.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies & Libraries Used
- import pathlib
- import tensorflow as tf
- import matplotlib.pyplot as plt
- import numpy as np
- import pandas as pd
- import os
- import PIL
- from glob import glob
- from tensorflow import keras
- from tensorflow.keras import layers
- from tensorflow.keras.models import Sequential
- from tensorflow.keras.layers import Dense, Dropout, Activation, Flatten, Conv2D, MaxPooling2D
