# Fake news detection jupyter :zipper_mouth_face:
Experimental code to build a machine learning model that would most accurately detect fake news.

## Overview :memo:
To detect fake news I have used dataset from the [kaggle website](https://www.kaggle.com/c/fake-news) that contains 20800 labeled atircles as true and fake news. In the preprocessing process I have used the following methods:
- removing all characters besides those in the alphabet and numbers
- lowering the text
- removing stop words
- stemming

After applying visualization, I have detected the main theme of the dataset, which is **"US Presidential campaign in 2016"**. The machine learning models that I have used are:
- Decision Tree Classifier
- Decision Tree Prunning Classifier
- Multinomial Naive Bayes Classifier
- Linear Support Vector Classifier

## Conclusions :bar_chart:
I would recommend to use Decision Trees when visualization of the chain of rules is needed for understanding the patterns of how the algorithm classifies the news. I would recommend to use Multinomial Naive Bayes, when precision of fake news is important and recall of fake news is not necessary. I would recommend using Linear Support Vector, when overall robustness of detecting fake news as well as true news is required.

## Improvements for future work :hammer:
- Do 10-cross validation on training and testing data
- Check how algorithms work with different sets of parameters
- Check more classifiers

## Author :pencil2:
Norbert Nieżorawski
