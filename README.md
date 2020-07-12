# Clinical-BCI-Challenge
Codes for submitted results

1. Within Subject

XGBoost Classifier has been used to evaluate the test data. The classifier has been trained with the train data given in https://github.com/5anirban9/Clinical-Brain-Computer-Interfaces-Challenge-WCCI-2020-Glasgow and is used to classiy the test data.

More about XGBoost Classifier can be found in the below link
https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/

Execution: The code is directly executable on Google Colaboratory but with an exception of loading data into drive and setting the path in the code.

2. Cross Subject

Deep Learning has been used to classify the given data. The classifier has been trained with the train data given in https://github.com/5anirban9/Clinical-Brain-Computer-Interfaces-Challenge-WCCI-2020-Glasgow and is used to classiy the test data. Our Algorithm uses CNN and LSTM in its architecture. 

The algorithm is adapted from the below paper
@article{Karim_2019,
   title={Multivariate LSTM-FCNs for time series classification},
   volume={116},
   ISSN={0893-6080},
   url={http://dx.doi.org/10.1016/j.neunet.2019.04.014},
   DOI={10.1016/j.neunet.2019.04.014},
   journal={Neural Networks},
   publisher={Elsevier BV},
   author={Karim, Fazle and Majumdar, Somshubra and Darabi, Houshang and Harford, Samuel},
   year={2019},
   month={Aug},
   pages={237–245}
}

Execution: The code is directly executable on Google Colaboratory but with an exception of loading data into drive and setting the path in the code.
