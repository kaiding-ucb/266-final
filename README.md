# Robust QA System with Data Augmentation
### By Kai Ding
### Date: Aug 4, 2023
----

### Table Of Contents:
- [Description](#description)<br>
    - [About the project](#about-the-project)<br>
    - [Repo files](#repo-files)<br>
- [Running Project](#running-project)<br>
    - [Requirements](#requirements)<br>
    - [Execution](#execution)<br>
----

### Description

#### About the project
This project is the final project for UC Berkeley 266 Natural Language Process. We used 3 in-domain datatsets including SQuAD (Wikipedia paragraphs with crowd-sourced questions and answers) , NewsQA (crowd-sourced based on CNN news), and Natural Questions (Google search queries), and evaluated with the 3 out-of-domain datasets include DuoRC (miscellaneous sources), RACE  (English language exams for middle and high school students) and RelationExtraction (miscellaneous). 

#### Repo Files
- `Robust QA System with Data Augmentation (Kai Ding).pdf`: PDF version of final report
- `266Final_data_augmentation.ipynb`: Main colab file which includes model performance in final report 
- `BackTranslation_processing.ipynb` : File for processing data for back translation
- Data files and saved models are included in this Google Drive link (https://drive.google.com/drive/folders/19Eoul3BOegVE33oqUgTXRQD0kZaDWzHA?usp=sharing)

#### Highlights
- Processing: Data processing to perserve over 90% of synonym replacement augmented examples to have answer in context span; over 50% for back translation
- Model Performance: Synonym replacement with p = 0.3 and n = 9 achieved best performance of 35.60 EM and 51.03 F1 score compared with baseline of 32.98 EM and 47.66 F1

----

### Running Project

#### Requirements

This project requires **Python 3.11** and the following Python libraries installed:

- [Python 3.11.3](https://www.python.org/downloads)                          (Coding Language)
- [NumPy](http://www.numpy.org/)                                            (For Scientific Computing)
- [Pandas](http://pandas.pydata.org)                                        (For Data Analysis)
- [matplotlib](http://matplotlib.org/)                                      (For Visualization)   
- [seaborn](https://seaborn.pydata.org/installing.html)                     (For Visualization)
- [scikit-learn](http://scikit-learn.org/stable/)                           (ML Library for Python)
- [tensorflow](http://tensorflow.org/install/)                              (Deep Learning Library)

#### Execution

In a terminal or command window, navigate to the top-level project directory `Forest_Cover-Type` (that contains this README) and run one of the following commands:

```bash
ipython notebook Phil_Kai_EDAv5_added_comments.ipynb
```  
or
```bash
jupyter notebook Phil_Kai_EDAv5_added_comments.ipynb
```
or if you have 'Jupyter Lab' installed
```bash
jupyter lab
```

-----
