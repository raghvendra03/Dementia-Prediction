# Dementia-Prediction
Analyzed and tried to understand if someone is likely to get Alzheimer’s 

## Table of Contents

1. Introduction
2. Overview of Data
3. Data Pre-Processing
4. Exploratory Data Analysis
5. Modeling

## Introduction
### What is Dementia

Dementia is a general term for a decline in mental ability severe enough to interfere with daily life. Memory loss is an example. Dementia is not a specific disease. It’s an overall term that describes a group of symptoms associated with a decline in memory or other thinking skills severe enough to reduce a person’s ability to perform everyday activities.

There is no one proper test which can tell you weather the patient has got dementia or it's very unpredictable as the Doctors do some carefull observations and checkups.

## Overview of Data

The main factor we determine here is CDR (Clinical Dementia Rating) which will help us in understanding the performance related to the dementia disease. Their rating is given as 
(0 = Normal, 0.5 = Very Mild Dementia, 1 = Mild Dementia, 2 = Moderate Dementia, 3 = Severe Dementia)

The other factore which affects this is: 
1. M.F - Gender
2. Age
3. EDUC - Years of education
4. SES - Socioeconomic status 
5. MMSE - Mini-Mental State Examination score (range is from 0 = worst to 30 = best)
6. eTIV - Estimated total intracranial volume, mm3
7. nWBV - Normalized whole-brain volume
8. ASF - Atlas scaling factor

## Data Pre-Processing

The dataset has to be imported and it will be split into two one for training purpose and other is for testing the dataset in the ratio 70% and 30% and the splitting is done random. We have checked for missing values and tried to fill it, there were some variables which has less or no effect in the analysis hence these have been removed from the dataset. 

## Exploratory Data Analysis

I have analysed the each variable with respect to the CDR with some visual graphs so as to understand what factors might affect or what might not, we got a better understanding as well from the Co-relation graph as well. The visulation is also done for all the variables with respect to the CDR and plots are easy to understand. 

## Model

Now the data has been trained and with the help of this analysis we will test the testing dataset. For testing the dataset I have used Classification based alrorithms and out of all other classification modle the best result I got was from Gradient Boosting and Support Vector Machine. 

Yes we can have some conclusion for this
- The data set available was very less, there has to be some more validation needs to be done which might help us in this.  
- The mani factors were not much affecting the CDR as per the co-relation graph.
