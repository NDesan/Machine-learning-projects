# Classification models for a real application : the Heart dataset

## Introduction 
### Goal of the practical sessions 

- Understand classification machine learning methods, from a methodological and practical point of view.
- To apply models and to tune the appropriate parameters on several data sets using the 'Python' language.
- To interprete 'Python outputs

## The data 

The "SAheart.txt" dataset stored a n = 462 sample of males in a heart-disease high-risk region of the Western Cape, South Africa. There are roughly two controls per case of CHD. Many of the CHD positive men have undergone blood pressure reduction treatment and other programs to reduce their risk factors after their CHD event. In some cases the measurements were made after these treatments. These data are taken from a larger dataset, described in Rousseaux et al, 1983, South African Medical Journal.

| Variable      | Description                                      |
|---------------|--------------------------------------------------|
| sbp           | Systolic Blood Pressure                          |
| tobacco       | Cumulative Tobacco (kg)                          |
| ldl           | Low Density Lipoprotein Cholesterol              |
| adiposity     | Adiposity                                        |
| famhist       | Family History of Heart Disease (Present, Absent) |
| typea         | Type-A Behavior                                  |
| obesity       | Obesity                                          |
| alcohol       | Current Alcohol Consumption                      |
| age           | Age at Onset                                     |
| chd           | Response, Coronary Heart Disease                 |

To read into R:
read.table("http://www-stat.stanford.edu/~tibs/ElemStatLearn/datasets/SAheart.data",
	sep=",",head=T,row.names=1)

## Purpose of the work 

The aim of the work of this section is to study classification models to be able to predict the value of the "chd" response variable (coronary heart disease) given the other variables (p=10).


