# Installation
! pip uninstall opencv-python -y <br>
! pip uninstall opencv-contrib-python -y  <br>
! pip install opencv-python==3.4.11.45  <br>
! pip install opencv-contrib-python==3.4.11.45  <br>
! pip install tqdm <br>

# Imports/Libraries
import argparse <br>
import cv2 <br>
import numpy as np <br>
import os<br>
from sklearn.cluster import KMeans<br>
from sklearn.svm import SVC<br>
from sklearn.preprocessing import StandardScaler<br>
from matplotlib import pyplot as plt<br>
from sklearn import svm, datasets<br>
from sklearn.model_selection import train_test_split<br>
from sklearn.metrics import confusion_matrix<br>
from sklearn.utils.multiclass import unique_labels<br>
from sklearn.metrics.pairwise import chi2_kernel<br>
from sklearn.model_selection import GridSearchCV<br>
from sklearn.metrics import accuracy_score<br>
from tqdm import tqdm<br>
import time<br>

# Repository Files
task1_INRIA.ipynb<br>
task2_objects.ipynb<br>
task2_flowers.ipynb<br>

