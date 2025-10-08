# udacity-blog-post-project

This projects analyses the salery distribution for Germany and the US for the stack overflow developer survey dataset from 2025 and investigates correlated. The business question to answer:

* What are the most correlated factors in Germany?
* What are the most correlated factors in US?
* What are the most correlated factors for the top 10% in Germany?
* What are the most correlated factors for the top 10% in the US?
* Are there any differences between Germany and the US?

# Data
Data for 2025 can be found on stack overflow: https://survey.stackoverflow.co/

# Enviroment setup
Testet with ```python 3.10.16```
Install enviorment: ```python -m venv .venv ; source .venv/bin/activate``` \
Install dependecies: ```pip install -r requirements.txt``` \
Run notebook: ```jupyter notebook stackoverflowdata.ipynb```

# Structure
Data can be found in: ```data/``` \
All code and plots in ```stackoverflowdata.ipynb``` 

# Data exploration
First, we take a look at the data structure and filter ah the relevant data. We plot the salary distrubutin that we are intested in and identify the features in the dataset that are accessible by algorithms suited for numerical and categorical data.


# Findings

In Germany and the US the correlation factors for high compensations are both years of experience and size of the company. However for the of 10% the picture is different. US top compensation correlate more to the field of data sience and small businesses where in Germany the high compensation corrlates to manager positions.

Details published here: https://medium.com/@walterbiernot/udacity-data-science-nanodegree-compensation-factors-for-developers-as-reported-by-stack-overflow-89d830ad211c

