# Note_Authentication_ML-app
The aim is to predict whether a given note is authentic given a number of measures taken from a photograph.

# Algorithm used
Random forest algorithm is used to build the model.

# Introduction
Whenever we go to the bank to deposit some cash, the cashier places notes in a machine that tells whether a note is genuine or counterfeit. The machine uses some classification techniques to do it. There are many machine learning algorithms for classification. Classification is a type of supervised machine learning. There are multiple machine learning algorithms in the classification.
We had used random forest algorithm, rather than we can use support vector machine or K nearest neighbour etc.

# About the data
Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images. The problem statement is quiet simple:

# Problem statement
There is a gray scale pictures of notes with a resolution of about 660 dpi. Wavelet Transform tool were used to extract features from images. We have four features['Variance', 'skewness', 'curtosis', 'entropy'] and we have to predict whether Bank Note is authentic or not.

I Have used RandomForestClassifier to predict wheather the note is authentic or not as problem is not that complex, I have Cleaned data with 0 Null values and just fitted the data and predict with 98% accuracy on test dat and created pickle file .

The pickle module implements a fundamental, but powerful algorithm for serializing and de-serializing a Python object structure.and additonally pickle is a binary file format

I have used streamlit to create a Web API
![Capture](https://user-images.githubusercontent.com/57935250/177293497-7959d5aa-14d6-48fc-a70e-afe500c0f9f4.PNG)
 
