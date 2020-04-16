# Catch Me If You Can

## An prediction of credit card fraud through machine learning. 

A final project for Flatiron School by Alexander Benn

Email: alexander.benn99@gmail.com

LinkedIn: https://www.linkedin.com/in/alex-benn-13a308155/


### Project Goals

The aim of this project was to see whether I would be able to predict the potential for credit card fraud from a Kaggle dataset https://www.kaggle.com/mlg-ulb/creditcardfraud

I was inspired to approach this project through my past experiences in the legal sphere, and my personal interests in criminal law, in which I have worked in the past. I wanted to apply what I have learned a Flatiron to a real world situation where I feel machine learning and data science can play a key, and important role. 

### The Current State of Fraud in the UK

After the financial crash of 2008, credit card fraud decreased in the UK, potentially due to a lower rate of consumer spending. As the nation recovered, however, fraud began to rise again, culminating most recently in an increase of 19% between 2018 and 2019, with these transactions encompassing 7% of the total credit card expenditure. 

<img width="740" alt="fraud over time" src="https://user-images.githubusercontent.com/57803574/79466296-4be0e880-7ff4-11ea-8787-a59c07cb89fb.png">

There is, therefore, a pressing need to address this criminal activity as quickly, and efficiently as possible. 

It must be noted as a first principl though that not all fraud is an 'open and shut' case. In many situations an activity may look like fraud, but is not, or may have a much more complex reason behind it. A good example is if someone is taken in by a phishing scam, and ends up making transactions that, at the surface level, appear to be fraudulent, despite that individual not committing an offence. This must be taken into account, and my models are only to inform, not to decide. 

### Machine Learning and Fraud

As fraud encompassess patterns and quantifiable numeric activity, it is prudent to use a classifier machine learning model. This will identify whether an activity falls towards the 'fraudulent' or 'non-fraudulent' end of the spectrum. Through this, it is possible to uncover what constitutes a 'suspicious' activity, and offer it to the relevant authorities for further investigation.

My findings in this project produced a model of eventual 94% train accuracy, and 99% test accuracy. These numbers, whilst demonstrating a potential very solid model, have a couple of caveats. One is that I was using a very clean dataset that had no missing values, and was clearly provided for pracitcing such work. The second is that as there was a class imbalance of 99% - 1% (non-fraud to fraud), the model is potentially very good at identifying not-fraud. This in itself can be useful, but as always such models must be assessed from a cohesive, objective standpoint. 

### Conclusions Drawn

My project demonstrates that 'fraudness' is certainly a classifiable target for machine learning, but the dataset itself posed an issue. As the data is anonymised to protect the individuals it concerns, it is not possible to draw concrete conclusions from my results. I have successfully identified several variables which have a significant impact on fraud, and would bear further investigation. This said, given that I do not know what these features actually represent, I cannot state what I feel would be the best areas to target.

<img width="987" alt="featurescc" src="https://user-images.githubusercontent.com/57803574/79466300-4daaac00-7ff4-11ea-840b-da15c0aa838f.png">


On the other hand, in future if I were able to gain access to a non-anonymised dataset, I have full confidence that my model would be able to provide valuable and actionable data to whatever private or public sector groups would have need of it. 
