# ADDI Alzheimer's Detection Challenge
This repository includes the approach and notebook for ADDI Alzheimer's Detection Challenge hosted by ADDI and AIcrowd. Since the data is private and confidential, this repository only provides methods and approaches for the one who want to participate any similar machine learning contests.

🕵️ **Introduction**

The Clock Drawing Test (CDT) is a simple test to detect signs of dementia. In this test the patient is asked to draw an analog clock with hands on the clock indicating ‘ten minutes past 11 o’clock.’ The test can be done on a blank paper or on a paper with a pre-drawn circle. This single test may be sensitive to dementia because it involves many cognitive areas that can be affected by dementia, including executive function, visuospatial abilities, motor programming, attention, and concentration. A qualified doctor then examines the drawing for the signs of dementia.

There are other widely acceptable scoring methodologies that are usually followed for scoring clocks drawn during cognitive assessment. The results from cognitive assessments by CDT are used to diagnose underlying cognitive disabilities, including Alzheimer’s disease.

![image](https://user-images.githubusercontent.com/30295013/121708931-09a32200-caa6-11eb-9216-d7af83414072.png)

✔  **The Task**
The challenge is to use the features extracted from the Clock Drawing Test to build an automated algorithm to predict whether each participant is in one of three phases:

1)    Pre-Alzheimer’s (Early Warning)
2)    Post-Alzheimer’s (Detection)
3)    Normal (Not an Alzheimer’s patient)

In machine learning terms: this is a 3-class classification task.

💾 **Dataset**

Each row in the data set represents the results from one clock drawing test of a single participant. The data set contains ~121 features(exact feature descriptions can be found [here](Feature-Documentation.pdf)).

**Training data**

Training data consists of 32,778 observations, which is a stratified random sample based on class labels of the original dataset. The labels are present as (Pre-Alzheimer’s, Post-Alzheimer’s, and Normal).

**Testing data**

The test data set consists of roughly 1,473  observations without label information. For each row predict a label (Pre-Alzheimer’s, Post-Alzheimer’s, and Normal). 

🔍 **Approach**

1.  Data Explore
2.  Pre-processing
3.  Feature Engineering
4.  Model Selection
5.  Hyperparameter Tuning
6.  Make the prediction and generate the result

Detailed code can be found [here](ADDI_Alzheimers_Detection.ipynb).

 

