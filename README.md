# Learning_Project_Solving_Data_Probelms
Udacity_Learning

## P1_factors.ipynb
- This is the notebook of part 1. It is aiming at solving the question about what factors that can influence the prices.
- And these libraries are needed: pandas, numpy, collections, matplotlib and Seaborn. Pandas and numpy are used for saving and dealing with data, and the rest libraries are used mainly for visualization propose.
- It produces 2 figures in total, both of them are heatmap type and can clearly show the connection between factors and prices.

## P2_predict.ipynb
- This is part 2 which is aiming at building and training the model to predict the prices.
- Besides numpy and pandas, I also use sklearn to split the training set and test set, as well as the mean squared error. And keras is a common used in deep learning.
- The model only trained for 50 epoches but it should be well enough to predict.
- At last, 2 figures are generated to show the predict performance in a visual way.

## P3_review.ipynb
- Part 3 is aiming at finding the relation between the number of reviews and prices.
- In this part, besides numpy, pandas and seaborn, a strong language processing library is used to analyse each comments. Sentiment Intensity Analyzer in NLTK is used to analyse the comments and get their polarity score.
- After processing the comments using NLTK, we will find that, most of comments are 0 negative polarity. In other words, most of comments are either positive or neutral. So that it is reasonable that the number of reviews do not influence the prices. And two figure is generated here to summarize and will help to understand that.
