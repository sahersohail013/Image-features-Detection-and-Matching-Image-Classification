# Installation
! pip uninstall opencv-python -y <br>
! pip uninstall opencv-contrib-python -y  <br>
! pip install opencv-python==3.4.11.45  <br>
! pip install opencv-contrib-python==3.4.11.45  <br>
! pip install tqdm <br>

# Imports
import argparse
import cv2
import numpy as np 
import os
from sklearn.cluster import KMeans
from sklearn.svm import SVC
from sklearn.preprocessing import StandardScaler
from matplotlib import pyplot as plt
from sklearn import svm, datasets
from sklearn.model_selection import train_test_split
from sklearn.metrics import confusion_matrix
from sklearn.utils.multiclass import unique_labels
from sklearn.metrics.pairwise import chi2_kernel
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import accuracy_score
from tqdm import tqdm
import time
