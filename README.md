# text_analytics_nltk_ensemble_models
This repository contains all the files used for building several ensemble models and also a text analysis exercise utilizing nltk corpus.<br>
The coding language used here is Python Programing.

## DataSet:
- Election Data (Election_Data.xlsx).

## Code File: (.ipynb)
- code_file.ipynb

## Business Report: (.pdf)
This report provides a detailed explanation on approach used, record inferences and insights to predict exit polls & also speech analysis of three of the Presidents of the United States of America.<br>

- Several models are used in predicting exit poll.<br>
> Linear <br>
> > -  Logistic Regression<br>
> > -  LDA<br>

> Non Parametic <br>
> > -  KNN<br>

> Probabilistic<br>
> > -  Naive Bayes<br>

> Tree Based Ensemble<br>
> > - Random Forest <br>
> > - Bagging <br>
> > - Boosting <br>

- Text analysis techniques (Bag of Words) had been leveraged on the inaugural corpora from the nltk.

## Libraries used:
> pandas<br>

> numpy<br>

> seaborn<br>

> matplotlib<br>
> > - pyplot

> sklearn<br>
> > - preprocessing - LabelEncoder<br>
> > - model_selection - train_test_split, GridSearchCV<br>
> > - linear_model - LogisticRegression<br>
> > - metrics - roc_auc_score, roc_curve, classification_report, confusion_matrix, plot_confusion_matrix<br>
> > - discriminant_analysis - LinearDiscriminantAnalysis<br>
> > - naive_bayes - GaussianNB<br>
> > - neighbors - KNeighborsClassifier<br>
> > - ensemble - BaggingClassifier, RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier<br>

> nltk<br>
> > - corpus - inaugural<br>

> string<br>

> re<br>

> wordcloud<br>
> > - WordCloud,STOPWORDS<br>

## How to run the code?
- Fork & Clone the repository
- Install the above libraries (virtual environment recommended) if not available using the command `pip install` in terminal
- Open the Code file and run all the cells. (Same Folder hierarchy as in repository to be used)


**This detailed analysis was performed by me as a part of my course work in Post Graduate Program in Data Science & Business Analytics**
