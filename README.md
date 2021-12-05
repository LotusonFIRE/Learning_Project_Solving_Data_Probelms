# Installations
- Those libraries are used in this project: pandas, numpy, collections, matplotlib, seaborn, sklearn, keras and nltk.
- To use the SentimentIntensityAnalyzer in nltk, the following code will need to run in python shell first:
> import nltk  
nltk.download('vader_lexicon')

# Project Motivation
It is cool to use machine learning models to predict the prices of listings. And to complete this task, it is necessary to find out the 
influential factors behind the prices. So that in this project, I will first look at the factors, then try to build a model that can predict the prices.

# File Descriptions
### P1_factors.ipynb
- This is the notebook of part 1. It is aiming at solving the question about what factors that can influence the prices.
- Pandas and numpy in this part are used for saving and dealing with data, and the rest libraries are used mainly for visualization propose.
- It produces 2 figures in total, both of them are heatmap type and can clearly show the connection between factors and prices.

### P2_predict.ipynb
- This is the notebook of part 2 which is aiming at building and training the model to predict the prices.
- Besides numpy and pandas, I use a function in sklearn to split the training set and test set, as well as the mean squared error function. And keras is common-used in deep learning.
- The model only trained for 50 epoches but it should be well enough to predict.
- At last, 2 figures are generated to show the predict performance in a visual way.

### P3_review.ipynb
- Part 3 is aiming at finding the relation between the number of reviews and prices.
- In this part, besides numpy, pandas and seaborn, a strong language processing library is used to analyse each comments. Sentiment Intensity Analyzer in NLTK is used to analyse the comments and get their polarity score.
- After processing the comments using NLTK, we will find that, most of comments are 0 negative polarity. In other words, most of comments are either positive or neutral. So that it is reasonable that the number of reviews do not influence the prices. And two figure is generated here to summarize and will help to understand that.

# Run
The notebooks of this project can be run from top to bottom one block by one as the blocks in every notebooks are all in the correct order.

# Acknowledgements
The deep learning model used in part 2 is inspired from the article below:
- https://www.kaggle.com/amritanshk/price-prediction