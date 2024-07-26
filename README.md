# ClassificationModelsForTabularData
### Machine learning models for the classification of data given in tabular form

This project is about developing a few machine learning models, that are going to be used to classify data given in tabular form (tabular data). More specifically, this git repository contains two different sub-projects:

- The **fetal_health.ipynb** file is a project where given a dataset that contains the characteristics of a fetus taken from the examination of a pregnant woman by a cardiotocogram in a tabular form, I developed some machine learning models to assess the health of the fetus according to these characteristics. Based on some characteristics of the fetus (i.e. fetal movement, uterine contractions, prolongued decelerations, etc), the machine learning models I developed were able to predict the health of the fetus (**Normal**, **Suspected for pathology** or **Pathological**) in a high level of accuracy. The predictions were made based on the values of the characteristics of the fetus in each case. The last column of the dataset ("fetal health") takes 1.0, 2.0 & 3.0 as values which correspond to "Normal", "Suspected for pathology" and "Pathological" examination result. Based on the values of the other characteristics/columns, the machine learning models are going to predict the value of this column and draw conclusions about the health of the fetus.

**Dataset used**: https://archive.ics.uci.edu/dataset/193/cardiotocography

- The **weather_temperature.ipynb** file is the second project where given another dataset that contains measurements of the weather that have taken place in over than 1000 cities, I developed some machine learning models to estimate the average temperature of a city in the world. The column of the dataset named "avg_temp_c" is the one we are interested in and describes the average temperature of a city per day. The machine learning regression models that were developed used all the information that the dataset provided (i.e. season, snow depth, precipitation, wind speed, etc) to predict the value of this column named **"avg_temp_c"**, which is the average temperature of the city described.

**Dataset taken from**: https://dev.meteostat.net/guide.html

The code is provided in the form of Google Colab notebooks.
