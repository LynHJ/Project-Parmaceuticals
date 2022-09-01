# Project-Parmaceuticals

## Background

This is a task regarding ten types of pharmaceuticals which are used as anti-skin-cancer drug regimens. 

I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumour growth were treated with a variety of drug regimens. Over the course of 45 days, tumour development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.  

They have also asked for a technical report of the study and a top-level summary of the study results.  

### Source

There are two data sets, a file of Mouse_Data.csv and a file of Study_Result.

### Data Analysis

To make sure my analysis is unbiased.I will do some calculations to check the datasets I have received  
1. Remove duplicated data  
2. Based on each pharmaceutical,calculating the mean, median, variance, standard deviation, and SEM of the tumor volume.  
3. All the pharmaceuticals should be used in similar durations.  
4. Check the mice'sex laying out.  
5. Picking up four pharmaceuticals which have lowest results of SEM of the tumor volume, and comparing via box plots.  
6. Checking the relation between tumour size and timeframe on the pharmaceutical which shows the best result.  
7. Calculating the relation between tumour size and body size. 

![alt](https://github.com/LynHJ/Pymaceuticals/blob/2cb0f6bd5874f10ca0940cfbcb1fba0dc42f16ab/OutputData/DA.png)  

### Advanced Data Analysis

![alt](https://github.com/LynHJ/Pymaceuticals/blob/2cb0f6bd5874f10ca0940cfbcb1fba0dc42f16ab/OutputData/ADA.png)  

1.	Statistically, the dataset is too small as size of each group (based on medicine)'s sample is only around 200 . If each group of population is only that much, then the standard deviation and standard error might be too large. In another word, the analysis based on this dataset might have test errors.
2.	Due to finding out that the dataset contains duplicate data and the number of test times scientists using in each drug group is not the same, I recommend to my client that they have to control variables carefully in the future experiments because control accuracy can increase the data credibility.
3.	Based on this dataset, Capomulin is relatively the best anti-cancer pharmaceutical for squamous cell carcinoma (SCC). However, if our client is willing to do extra tests on the Ramicane group. Ramicane could be the best drug as its performance on curing cancer is better than Capomulin’s.


## Content:

Project  
|  
|Project-Parmaceuticals-|  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;|-data:&emsp;&emsp;&emsp;&nbsp;|-Mouse_metadata.csv   
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-Study_results.csv   
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;|-OutputData:|-ADA.png  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;|-DA.png  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;|-Pymaceuticals.ipynb.ipynb  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;|-Drug Regimens Report.pdf    
|-README.md 

## Installation

1.conda env create -n PythonData --file intro_python_requirements_osx.yml python=3.7.7    
2.conda install matplotlib    
 



