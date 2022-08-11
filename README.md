<img src="https://github.com/hyun-hyang/ResumEmphasizer/blob/main/logo/logo%20ver.2.png" align="left" hspace="1" vspace="1" width="304" height="120">



# [ResumEmphasizer - AI writer](http://44.227.122.114/)



AI writer, making bullet points on the basis of Job Descriptions(JDs).

It is a short term training project with peoplespace.


**Language :** Workframe: docker, wordpress, MySQL, Apache, php, spaCy

**Slogan :** Resumes with Impact: Creating Strong Bullet Points!


## Introduction
The project uses techniques in Machine Learning and Name Entity Recognition (NER) Model.

# **WHY ResumEmphasizer**

We refine your resume further. Our aim is to make your resumes pass through the HR filter by highlighting your strengths using Ai trained to find Bulletpoint.

We make your resumes pass through HR filter.

Score your resume compared to other applicants.

Trained AI looks for bulllet points.

# Main activities
* [Set targets](https://github.com/hyun-hyang/ResumEmphasizer/tree/main/Persona) and devise a service.
* [Design websites](http://44.227.122.114/) with wordpress.
* [Annotate datas](https://github.com/hyun-hyang/ResumEmphasizer/tree/main/Data_annoctated) with doccano.
* [Train AI](https://github.com/hyun-hyang/ResumEmphasizer/tree/main/trained_data)  with spaCy.

# Revenue Cost Model
| Revenue | Cost |
|:--:|:--:|
|  service charges | employee wages       |
|  advertising fees | network usage fees       |
|  sponsorship fees | Extra fees e.g. colab payments       |


## Directory Details

## [Data](https://github.com/prateekguptaiiitk/Resume_Classifier/tree/develop/Data)

- **CVs.txt :** Contains 250 extracted resumes in text format from [indeed.com](https://www.indeed.com), file format is converted to txt to be used at Docanno.
- **collectCV.py :** Python script to automate the process of extracting CVs from indeed.com. While this program is running, every new text copied to clipboard is saved as a CV in **CVs/** directory in text format.
- **jobdescription.csv :** CSV file containing cleaned job descriptions from Kaggle. Dataset can be found [here](https://www.kaggle.com/c/job-salary-prediction/data)
- **resume.ipynb :** ipynb file containing trained data of resumes from google colab.
- **jd.ipynb :** ipynb file containing trained data of job descriptions from google colab.
