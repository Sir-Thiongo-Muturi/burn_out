# Background
Burnout rate is defined as an occupational phenomenon arising from unmanaged, chronic workplace stress (WHO, 2019). Burnout (with regards to an employee) is characterized by exhaustion, downturn in professional efficacy, and increasingly negative feelings toward their job.  
## Problem
There are a number of factors that are believed to cause burnout. Burnout has negative effects on employees and firms that they work in. Burnout can lead to depression, poor health and strains in marriages or family. Burnout can also lead to reduced employee productivity at work, high worker turnover rate, absenteeism, etc. As such, it is important to identify factors that accelerate burnout rate at work in order to mitigate these vices.
## Purpose
Some of the potential predictors for burnout rate include gender, company type, work-from-home availability, designation, resource allocation, and mental fatigue. The purpose of this study is to identify the true predictors of burnout rate with the aim of developing a model that can predict the burnout rate given some values of the predictor variables.
# Data Preprocessing
install required packages-
``` R
install.packages("pdp")
install.packages("vip")
install.packages("gbm")
install.packages("glmnet")
install.packages("caret")
install.packages("psych")
install.packages("corrplot")
install.packages("randomForest")
install.packages("ROCR")
install.packages("Metrics")
library(Metrics)
library(psych)
library(tidyverse)
library(rpart)
library(rpart.plot)
library(dplyr)
library(gbm)
library(vip)
library(pdp)
library(mice)
library(magrittr)
library(caret)
library(glmnet)
library(corrplot)
library(randomForest)
library(ROCR)
```


