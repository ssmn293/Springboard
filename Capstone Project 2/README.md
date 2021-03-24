# Capstone Project 2 - Toxic Comment Classification

## Introduction
There is an increasingly high number of toxic behaviour and comments over the internet which are making it difficult to have meaningful discussion on the net. As the world is becoming more and more technologically involved and people demonstrate more presence on the internet compared to in real life, it is important to make it a healthy and safe place to express opinions. 
One does not need to look far but at Youtube, where presence of toxic and hatred comments in ubiquitous in almost any video. This has led many Youtube channels to disable the comment section, which in itself might be a bit of an extreme measure given the fact that genuine commentators might be interested in the content and want to engage in meaningful discussion. The need for a mechanism to deal with outright toxic and unhealthy comments are more than ever relevant in this day and age.

## The Dataset

Dataset: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/
The dataset chosen for addressing this issues is the Toxic Comment Classification Challenge by Kaggle that was published in March 2018. Conversation AI is a research initiative by Jigsaw and Google aiming at improving online conversation. They have created a lot of publicly available models but there are still errors involved. This competition challenged other to find a model that can better detect negative online behaviour.
This dataset contains Wikipedia comments that have been rated for toxic behaviour. There are 6 classes for 6 types of toxic behaviour including: toxic, severe_toxic, obscene, threat, insult, identity_hate. There are 159,571 comments in the training set (which also includes comments that are rated as neutral, meaning being scored 0 for all classes). The test set include 63,978 comments.

## Files included in this folder
1. Capstone 2 Report
2. Codes
3. Presentation Slides

## Conclusion from findings
The results from all models are quite promising with high average ROC-AUC in all models.
	Logistic Regression	Naive Bayes	Decision Tree Classifier	Random Forest Classifier
Average ROC-AUC	0.979	0.948382	0.7941	0.9668![image](https://user-images.githubusercontent.com/60270500/112245842-12632500-8c28-11eb-971e-5c3d5006cce3.png)

Online community is no longer what it used to be and toxic comments disrupt the healthy discussion that can exist and drive serious users away. Social media platforms such as instagram and facebook and among others can certainly make use of a more effective way of filtering toxic comments to ensure a better online experience for all.
While Instagram has setting for users to manually filter a set of keywords, it should not be up to the users to have to ensure they are not exposed to a toxic online environment.
