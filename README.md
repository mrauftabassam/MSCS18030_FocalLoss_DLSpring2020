# MSCS18030_FocalLoss_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

# Dataset
Dataset is available at the following drive link:
https://drive.google.com/open?id=1zMf3ODRPQ_YNIwf2a8TxlXkg2JXPfyra

# Task 1: Finetune pre-trained CNN models

### By Using VGG16 without focal loss: 
Code for this experiment is attached named as "covid19_classification_01.ipynb"

    Training Accuracy: 92%
    
    Validation Accuracy: 94.9%
    
    Confusion Matrix on Test Data: 
|               |             |            | Predicted Values |          |          |
|:-------------:|:-----------:|:----------:|:----------------:|:--------:|:--------:|
|               |             | “covid-19” |    “pneumonia”   | “normal” | F1 Score |
|               |  “covid-19” |     84     |        58        |    55    |   0.59   |
| Actual Values | “pneumonia” |      0     |       3939       |    55    |   0.95   |
|               |   “normal”  |      1     |        307       |   1672   |   0.88   |

    Confusion Matrix on Validation Data: 
|               |             |            | Predicted Values |          |          |
|:-------------:|:-----------:|:----------:|:----------------:|:--------:|:--------:|
|               |             | “covid-19” |    “pneumonia”   | “normal” | F1 Score |
|               |  “covid-19” |     14     |        11        |     3    |   0.65   |
| Actual Values | “pneumonia” |      1     |       393        |     4    |   0.96   |
|               |   “normal”  |      0     |        15        |    184   |   0.94   |
		
    
### By Using RES18: 
Code for this experiment is attached named as "covid19_classification_02.ipynb"

    Training Accuracy: 89.74%
    
    Confusion Matrix on Train Data: 
|               |             |            | Predicted Values |          |          |
|:-------------:|:-----------:|:----------:|:----------------:|:--------:|:--------:|
|               |             | “covid-19” |    “pneumonia”   | “normal” | F1 Score |
|               |  “covid-19” |      7     |        145       |    42    |   0.07   |
| Actual Values | “pneumonia” |      0     |       3860       |    119   |   0.93   |
|               |   “normal”  |      2     |        283       |   1702   |   0.88   |


    Validation Accuracy: 91.08%

    Confusion Matrix on Validation Data: 
|               |             |            | Predicted Values |          |          |
|:-------------:|:-----------:|:----------:|:----------------:|:--------:|:--------:|
|               |             | “covid-19” |    “pneumonia”   | “normal” | F1 Score |
|               |  “covid-19” |      0     |        26        |     1    |   0.0    |
| Actual Values | “pneumonia” |      0     |       393        |     6    |   0.94   |
|               |   “normal”  |      0     |        20        |    178   |   0.92   |
=================================================================

#### Note: Furture details are reported in attached report named as "Report_A5b.pdf"

