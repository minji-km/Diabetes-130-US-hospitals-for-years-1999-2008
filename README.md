# Diabetes-130-US-hospitals-for-years-1999-2008
Data analysis and prediction on hospital readmission

The data set represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. From this dataset, we want to know how well we can predict hospital readmission and what are the features that are the most significant predictors among these features.

After running a few models with scikit learn, we can see that oversampling exponentially increased the proporiton of true positives of the decision trees. 
Gradient boosting's accuracy also improved after oversampling despite the poor results. Finally, the best model among the 6 (decision tree, gradient boosting and random forest, with and without oversampling) is the random forest with oversampling one which gives the most accurate prediction.


Run commands :

To run the notebook correctly, you have to install pandas and other libraries and also this one :

```!pip install imblearn```

To run the API, run a windows terminal :

```pip install Flask --user```

```pip install matplotlib --user```

```pip install seaborn --user```

```pip install scikit.learn --user```

```pip install pandas --user```

```pip install requires.io --user```

then go to the python projet folder :

```cd python projet```

and run 

```python "test.py"```

copy the http: link and paste it on a web browser ! 
