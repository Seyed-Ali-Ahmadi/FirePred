# FirePred

We will provide the codes for our paper "FirePred: A hybrid multi-temporal convolutional neural network model for wildfire spread prediction" in this repository.

# Abstract
Wildfires are a type of natural disaster that can cause extensive damage to both the environment and property. Recently, deep learning (DL) methods have been proposed for predicting wildfire spread. However, these studies have only used combined features with equal weights and have not considered their different temporal resolutions (i.e., hourly, daily, and constant). As such, this study proposes a hybrid multi-temporal convolutional neural network (CNN) model called FirePred. 177 wildfire events are utilized along with related environmental variables between the years 2002 and 2018 in British Columbia, Canada. To determine the best configuration of parameters and settings for the model, the study evaluated different combinations of loss functions, padding sizes, batch size, and thresholds.  An F1-score of 94% is achieved by the best set of parameters. To investigate the transferability of the proposed model, a dataset comprising 10 instances of wildfires that occurred in Alaska from 2016 to 2019 and a wildfire occurred in Nova Scotia in 2023 were utilized. The findings revealed that the performance of the model can be influenced by regional parameters. Finally, the implementation of an uncertainty estimation procedure revealed  that edges of the wildfire contribute the most to the uncertainty. 


![Multitemporal NN model](https://github.com/Seyed-Ali-Ahmadi/FirePred/assets/53389122/9be061a1-9b62-49c3-9db2-cd2c2f2e04e3)
