<img src="https://github.com/hyun-hyang/ResumEmphasizer/blob/main/logo/logo.jpg" align="left" hspace="1" vspace="1">

# ResumEmphasizer - AI writer


AI writer, making bullet points on the basis of Job Descriptions(JDs).

It is a short term training project with peoplespace.



 **Language: ** 
Workframe: docker, wordpress, MySQL, Apache, php

 **Slogan: ** Resumes with Impact: Creating Strong Bullet Points


## Introduction
The project uses techniques in Machine Learning and Name Entity Recognition (NER) Model.

## Directory Details

## [Data](https://github.com/prateekguptaiiitk/Resume_Classifier/tree/develop/Data)

- **CVs.txt :** Contains 250 extracted resumes in text format from [indeed.com](https://www.indeed.com), file format is converted to txt to be used at Docanno.
- **collectCV.py :** Python script to automate the process of extracting CVs from indeed.com. While this program is running, every new text copied to clipboard is saved as a CV in **CVs/** directory in text format.
- **jobdescription.csv :** CSV file containing cleaned job descriptions from Kaggle. Dataset can be found [here](https://www.kaggle.com/c/job-salary-prediction/data)

