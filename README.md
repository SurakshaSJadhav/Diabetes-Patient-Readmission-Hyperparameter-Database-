# Diabetes-Patient-Readmission-Hyperparameter-Database-


The data we will be working with is
readmission of diabetic patient’s data. The
outcome is focused on the management of
hyperglycemia in patients that are
hospitalized. This factor has an important
bearing in terms of morbidity and mortality.
In the dataset, we will see the impact of
various clinical practices in readmission rates.
The dataset constitutes the clinical care at
130 hospitals and coherent networks in the
US for the last 10 years(1999-2008). Multiple
features are included such as outcomes of
patient and hospital. Information was
extracted from the databases for situations
that satisfied the following criteria :
1) If the hospital admission is an
inpatient encounter.
2) If it is a diabetic encounter. The type
of diagnosis which was entered.
3) If the length of the patient's stay was
at least 1 day and at most 14 days.
4) if during the encounter Laboratory
tests were carried out.
5) If medications were doctored during
the encounter.


# Method

Parameters that are stated in prior to running
a machine learning algorithm and that have
a colossal effect on the predictive power of
statistical models are known as
Hyperparameters. The aim to creating
constructive models is the comprehension of
the relative significance of a hyperparameter
to an algorithm and also the range of the
values of the hyperparameter is an integral
aspect to tuning the hyperparameters in the
model construction. The database for the
Hyperparameters is a public resource with
algorithms, tools, and data which allows the
user to visualize and comprehend how to
choose the hyperparameters in order to
maximize the predictive power of the
models. This database for the
hyperparameter is created by running
millions of hyperparameters values on
multiple databases and calculating the
individual exception of each hyperparameter
on the quality of the model. Currently, the
hyperparameter database analyzes the effect
of hyperparameters on the following
algorithms: Distributed Random Forest
(DRF), Generalized Linear Model (GLM),
Gradient Boosting Machine (GBM). Naïve
Bayes Classifier, Stacked Ensembles, Xgboost
and Deep Learning Models (Neural
Networks). We can also build the models
using the hyperparameter database that can
predict the hyperparameters without
searching or visualizing the statistical
concepts such as bias/variance tradeoff.

# Result

The dataset was selected, and we ran AutoML
on the dataset and decided the Target, which
in our case is the readmission of the diabetic
patients. We ran the AutoML for three
different run times i.e.
1) 500sec
2) 1000sec
3) 1500sec
After fetching the AutoML leaderboard we
stored the models for future reference. The
hyperparameters for all the run time is
extracted and stored. These extracted
Hyperparameters for each model is stored in
JSON or CSV. The Meta_Data for every run is
obtained. Knowledge of the relative
importance of a hyperparameter to an
algorithm and its range of values is crucial to
hyperparameter tuning and creating
effective models.
For example, we have considered a GBM
model where we noticed an increase in the
AUC (metric) with an increase in the number
of trees (viz; Hyperparameter).
