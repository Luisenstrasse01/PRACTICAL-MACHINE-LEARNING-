# PRACTICAL-MACHINE-LEARNING-

## INTRO

In this document we will perform prediction with the dataset from Qualitative Activity Recognition [1] which is composed of 2 csv documents.

-Training: 19622 observations 

-Testing: 20 observations

Each observation corresponds to a time window of weight lifting (specifically dumbel lift) which records among other variables, values of accelerometers, gyroscopes and other devices in different parts of the body and dumbell.

The datasets have 160 variables and we will study with the training dataset the variable "classe" wich is a value from "A" to "D". [1] Class A corresponds to the specified execution of the exercise, while the other 4 classes correspond to common mistakes. Participants were supervised by an experienced weight lifter for recording this categorical variable.

The goal is to predict the variable classe with the testing dataset in 20 observations. We will only use the accelerometers records from belt, forearm, arm, and dumbell.

## REFFERENCES

[1]Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.
Read more: http://groupware.les.inf.puc-rio.br/har#ixzz6oG3Jb8sw
