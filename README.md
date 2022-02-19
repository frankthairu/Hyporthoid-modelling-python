# Week-8-Hyporthoid-modelling
Hyporthoid modelling

## a) Specifying the Question

We are building  a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid

##  b) Defining the Metric for success.

The model we will consider is the one that is able to effectively and optimally predict the target variable with 60% to 95%

## c) Understanding the context

The dataset that we will be using is Nairobi hospital thyroid dataset with the following columns:

column description

status - tells us if the patient is negative or has hypothyroidism

age - how old is the patient

sex - if the patient is male or female

on_thyroxine - true /False

query_on_thyroxine -true / false

on_antithyroid_medication - if the patient is on medication(true / false)

thyroid_surgery - if the patient has had thyroid surgery(true / false)

query_hypothyroid-true / false

query_hyperthyroid-true / false

pregnant - if the patient is pregnant,true or false(true / false)

sick - if the patient is sick,(true / false)

tumor - if the patient has tumor(true / false)

lithium-(true / false)

goitre - if the patient has goitre(true / false)

TSH_measured - if a blood test has been done to measure the hormone(yes/no)

TSH - thyroid stimulating hormone , tells the thyroid to release thyroid hormone to the blood.

T3_measured - if T3 measurement has been done(yes/no)

T3 - triiodothyronine , this is a thyroid hormone produced in the thyroid glands

TT4_measured -if TT4 measurement has been done(yes/no)

TT4 - thyroxine , the principla hormone from the thyroid gland.

T4U_measured - if T4u measurement has been done(yes/no)

T4U - thyroid hormone produced in the thyroid glands(thyroxine)/levothyroxine

FTI_measured - if FTI has been measured(yes/no)

FTI - free thyroxine index, it is considered more indicator of thyroid, obtained by nultiplying Total T4 and T3 uptake.

TBG_measured - if TBG has been measured.(yes/no)

TBG - thyroid binding globulin, binds thyroid hormones in circulation

## d) Recording the experimental design.

The following steps will be followed in conducting this study: 1.Define the question, the metric for success, the context, experimental design taken.

Read and explore the given dataset.

Read and explore the given dataset.

Define the appropriateness of the available data to answer the given question.

Find and deal with outliers, anomalies, and missing data within the dataset.

Perform univariate and bivariate analysis and recording our observations.

## e) Data Relevance

The data we will be using can be found in the link below

http://bit.ly/hypothyroid_data



Performing prediction using any of the two models Random forests, Ada boosted trees, and gradient boosted trees.
Perform optimization on our dataset by tuning our hyperparameters Perfom Polynomial, linear and rbf kernel function to build your SVM model and then evaluate their performance and pick the kernel that performs the best

