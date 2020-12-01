# DATA1030 - Fall 2020, Final Project
## Annie Phan, Master in Data Science, Class of 2021


# Content Overview
* [Introduction](#overview)
* [Dataset Link](#datasetlink)
* [Articles Consulted](#articlesconsulted)
* [Repository Organization](#repositoryorganization)
* [Technologies](#technologies)
* [Packages](#packages)

# Introduction

This repository contains my final project for the course DATA1030, Fall 2020. 

The project examines how social and educational factors impact students’ performance to allow educators to intervene as necessary. I use ML to predict if students will pass or fail based on information such as family background, socioeconomic status, previous grades, etc. The students pass if their final score is 10 and fail otherwise.  

The data is obtained from the UCI ML Repository and my project is based on the paper “Using Data Mining to Predict Secondary School Student Performance” by Cortez and Silva in 2008. 


# Dataset Link:
http://archive.ics.uci.edu/ml/datasets/Student+Performance


# Articles Consulted:

P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.


# Repository Organization:

├── Data/ 

├── Figures/ 

├── Results/  

├── Reports/ 

├── Src/ 

├── LICENSE 

└── README.md 

Raw and Preprocessed data files are in Data/

All generated figures are in Figures/

Model Results (predictions, saved models, etc) are in Results/

Report and Midterm Proposal (pdf versions) are in Reports/

Source codes (ipython notebooks or python files) are in Src/ 

# Technologies 

Python 3.7.3

# Packages Used in Analysis: 


pandas==0.25.0

pickleshare==0.7.5

plotly==4.1.1

scikit-learn==0.21.3

sympy==1.4

numpy==1.17.1

matplotlib==3.1.1
