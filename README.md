# Natural-Language-Processing-
This README complements the Jupyter Notebook provided. This is my first ever NLP task and 2 classifiers were tested (naive bayes and SVM).


In order for someone to run the code they would need to have downloaded the SemEval 2017 data, namely :

twitter-dev-data.txt
twitter-test1.txt
twitter-test2.txt
twitter-test3.txt
twitter-training-data.txt

Non-Standard Libraries : you may need to pip install these

SMOTE (pip install imblearn)
emoji (pip install emoji)


Figshare link : https://figshare.com/articles/software/SVM_pickle_1_/17170931 (this is where the pickled model of the SVM classifier can be found)

#Please use pickle to fit the SVM linear kernel model faster, otherwise it takes 10' to run.


The Notebook has thorough documentation and should be executed linearly as you go. The python version used was 3.8.8


Steps :

someone using the notebook should :


1)Download all libraries

2) Read Data

3) Apply SMOTE and TF-IDF to all datasets (relevant functions have been defined)

3) Proceed to the classifiers

#################################################################################################


Performance metrics (Averaged F1-Macro Scores) were judged for the 3 classes present in the dataset (Positive,Negative,Neutral)



This was my first ever NLP project be lenient :) 

I hope you enjoy the approach as much as i did
