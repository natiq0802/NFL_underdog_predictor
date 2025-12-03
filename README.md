# NFL_underdog_predictor
Repo for the final project for DSGA-1007, Programming for Data Science. We will try to predict underdog victories in the NFL using machine learning techniques. We use a variety of data sources, feature engineering and prediction models to accomplish this goal. We acknowledge the possibility that our model fails to reliably predict underdogs in a way that is better than the Vegas Lines, but regardless, this presents a great exercise about machine learning modeling as well as industry coding practices. It will actually prove useful to have the Vegas line as a point of reference: if our model is making the same predictions as the vegas line, then that would be signify our code is mostly on the right track :)

Our analysis covers the seasons between 2005 and 2015 (due to relative consistency in names and game rules over this period). 

**DISCLAIMER**: We are not doing this for gambling purposes, but rather to try and uncover patterns and trends previously undetected. This project is motivated purely by curiosity and has zero monetary incentives. 

Our project is divided into 4 notebooks, each serving its own unique function:
1. `Notebook-1.ipynb`: Data retrieval and loading
2. `Notebook-2.ipynb`: Data cleaning and standardizing
3. `Notebook-3.ipynb`: Exploratory analysis and visualizations
4. `Notebook-4.ipynb`: Machine Learning and predictions

We made each notebook in keeping with the principles of **modularization and testing**. As well as **abstraction**, which made it easier to share our work between members seamlessly. 

It also comes with two accompanying data files which are needed for the analysis and labelling:
1. `moneyline.csv`: Money line data for NFL games
2. `stats.csv`: Team statistics for NFL teams

The Python libraries we used (in no particular order):

Analysis:
- `pandas`
- `numpy`

Visualizations:
-  `matplotlib`
- `seaborn`
- `ipywidgets`

Machine Learning:
- `sklearn`

File handling and parsing
- `os`
- `re`
- `requests`
- `typing`
- `glob`
