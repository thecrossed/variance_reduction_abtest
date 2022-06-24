# About
This is a capstone project of the Udacity Data Scientist Nano-degree project. It tries different approaches for variance reduction, which is a industry-wide technique to increase sensitivety of business metrics.

You can also read the related blog [here](https://medium.com/@tianmin/variance-reduction-techniques-78887a496e2).

# Motivation
Questions to ask
1. What are the methods to reduce variance for hypothesis testing?
2. How much variance each method reduce for our dataset? (Starbucks customer AB testing public dataset)
3. How to use Python to implement each method?

# Requiments
Python libraries
pandas
numpy
math
plotly

# Description of each file
variance reduction.ipython is the main file showcasing the analysis
README.md file introduces the project at a high level
training_ab_starbucks.csv is the dataset for the analysis


# Summary of analysis
We adopted three techniques to reduce variance for the Starbucks customer dataset. The result is increasing the sample size doesn't bring us a clear reduction of variance, while on the other hand, changing the mean metrics into conversion rate and stratification significantly reduces the variance.

# Acknowledgement
Great gratitude to Udacity.com for setting up this nano-degree program, to Starbucks for sharing the public dataset, and to paper authors publishing their findings on this topic.