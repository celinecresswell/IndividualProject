# IndividualProject
A repository containing the supporting code for Part C individual project at Loughborough University.
All code was done in a Google Colab notebook and copied to Github for sharing.

## Table of Contents
1. General information
2. Technologies
3. Repository Contents
4. Methodology
5. Abbreviations

## General Information
Project Title: An evaluative framework of explainable machine learning methods
Purpose: To build a quantitive, objective framework for the evaluation of explainable artificial intelligence (XAI)
How does this code support the project?
This code was written to create the algorithms which the proposed framework would evaluate. The code classifies species based on extracted features from opto-acoustic recordings of aphids and beetles and also uses the environmental data collected.

Open source dataset utilised: Hassall, K. L., Dye, A. and Bell, J. R. 2020. Extracted features from opto-acoustic audio recordings of aphids and beetles. Rothamsted Research. https://doi.org/10.23637/rothamsted.981w8

##Technologies
*numpy: Version
*matplotlib: Version
*sns: Version
*bnlearn: Version

#Repository contents:
1. RFC.ipynb
  a. Random forest classifier notebook
2. SVM.ipynb
  a. Support vector machine notebook

#Methodology 
1. Both notebooks have the same data preprocessing:
  a. Importing basic librares and the dataset
  b. Dropping unneeded features from the dataset
  c. Handling missing values
  d. Removing species object classes with low instances
  e. Scaling
  f. Feature selection
  g. Data splitting for training and testing
  h. Data imbalance handling
2. Key difference between the two notebooks is the machine learning model used: Random forest classifier and support vector machine model.

#Abbreviations
RFC = Random forest classifier
SVM = Support vector machine
LMAG = log_maxAmp_g
LRAG = log_rangeAmp_g
LPG = log_power_g
LRMSG = log_rms_g
SEG = spectralEntropy_g
T = temp
H = humid
SP = species
FF = log_fundFreq

