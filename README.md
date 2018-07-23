# academic-harassment-data
Exploring and visualizing survey results of open survey on sexual harassment in academia using Pyspark, pandas, NLTK

## Introduction: Motivation

I learned about the “Sexual Harassment in Academia: Results of a Crowdsourced Survey” in SI 649, where the data was presented as a an option for our semester-long group project. At our first group meeting, we pulled up the dataset and discovered a messy, unwieldy collection of data about an extremely important topic. Our group surveyed the 3,000+ lines of survey responses and decided that it would be too time-intensive to extract clean data that we could subsequently visualize. We decided on another dataset.

However, the critical data scientist in me was hooked. As somebody who is passionate about using data to investigate social issues, I appreciated the importance of this unprecedented data. Thousands of individuals had revealed their experiences with sexual harassment and assault in academia, many apparently for the first time. These reports detailed the devastating effect these events had on their lives. This is vital, powerful data that deserves to have its story told.

At the same time, the issues with preprocessing and the unpredictability of free text responses contribute to the idea that we should wait for experts or well-funded research teams to dig into this data. I am eager to explore ways of doing data science that circumvent barriers by iterating quickly to generate important questions. I broke my project down into four main questions:
1) What are the main themes (or topics) in reports of harassment/assault event?

2) How do the descriptions of the aftermath of incidents differ between professor/faculty/department chair perpetrators and non-faculty perpetrators?
3) What language in incident descriptions is most predictive of whether the perpetrator was a professor/faculty/department chair or not? How powerful is this prediction?
4) Finally, what language in the incident report is most predictive of whether the respondent “left” or “quit” their position/academia/the discipline/etc? How powerful is this prediction (in general and relative to the professor model)?

## Explore Analysis Methods/Findings

In this repository you will find:
* The Sexual Harassment in Academia dataset as downloaded on April 4, 2018. A tthat time, 2,438 reports had been submitted between December 1st, 2017 and April 4, 2018
* A Jupyter Notebook (originally run on Databricks) with code to analyze the dataset using PySpark with MLLib, pandas, NLTK, etc.
* A .html representation of the noteobok
* A project report (look for an expanded blog post on critical data methods soon!)
