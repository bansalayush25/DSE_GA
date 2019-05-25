

# Dynamic Selection of fitness function in genetic algorithms for feature selection in software defect prediction

In this study, we consider three fitness functions, Accuracy, F Measure,and Voting and Validation, and use them to select features in twenty-four software datasets for feature selection. Based on the performance of a classifier on these selected features, using the DSF algorithm we select the fitness function which is most likely to correctly predict the defect susceptibility of a new class intance.


## Dataset used
All datasets for the purpose of this project have been taken from the PROMISE repository of open source software- http://openscience.us/repo/defect


## Using this repository
dataset/dataset contains all the preprocessed datasets which are input to DSE pipeline  
dataset/annotated contains output of first fold of cassification, including results of all three base ensembles and best ensemle for it  
dataset/DSF contains additional columns containing predictions of DSE and probabilities  
dataset/metrics includes performance metrics of all base ensmebles on softwares   
results contain performance metrics of DSF
