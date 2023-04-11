# Biomedical-Data-Analysis
This is a project for my machine learning course focusing on binary classification using K-Nearest Neighbors Algorithms. I aim to predict and classify patients into two classes: Normal and Abnormal 

# Data Source
https://archive.ics.uci.edu/ml/datasets/Vertebral+Column
Biomedical data set built by Dr. Henrique da Mota during a medical residence period in the Group of Applied Research in Orthopaedics (GARO) of the Centre MÃ©dico-Chirurgical de RÃ©adaptation des Massues, Lyon, France. The data have been organized in two different but related classification tasks. The first task consists in classifying patients as belonging to one out of three categories: Normal (100 patients), Disk Hernia (60 patients) or Spondylolisthesis (150 patients). For the second task, the categories Disk Hernia and Spondylolisthesis were merged into a single category labelled as 'abnormal'. Thus, the second task consists in classifying patients as belonging to one out of two categories: Normal (100 patients) or Abnormal (210 patients). We provide files also for use within the WEKA environment.

# Data Description:
Each patient is represented in the data set by six biomechanical attributes derived from the shape and orientation of the pelvis and lumbar spine (in this order): pelvic incidence, pelvic tilt, lumbar lordosis angle, sacral slope, pelvic radius and grade of spondylolisthesis. The following convention is used for the class labels: DH (Disk Hernia), Spondylolisthesis (SL), Normal (NO) and Abnormal (AB).

# Tasks:
## Pre-processing and Exploratory Data Analysis:
- Make scatterplots of the independent variables in the dataset
- Make boxplots for each of the independent variables
- Split into training and test sets
## Classification using KNN with Euclidean Metric
- Choose optimal k using cross-validation
- Plot the best test error rate against the size of training set
- Plot learning curve for different size of training set and test error rate
## Classification using KNN with Minkowski Distance:
- Find the optimal parameter
- Report the least test error rate
## Classification using KNN with Chebyshev Distance
## Classification using KNN with Mahalanois Distance
## Classification using KNN with weighted voting and various distance metrics
- Compare the best test errors for using weighted voting with Euclidean, Manhattan, and Chebyshev distances
