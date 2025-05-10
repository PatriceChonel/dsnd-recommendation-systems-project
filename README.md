# Software Engineering for Data Scientists 

This repository contains starter code for the **Software Engineering for Data Scientists** final project. Please reference your course materials for documentation on this repository's structure and important files. Happy coding!



# Recommendation System Project IBM Watson Platform


For this 4th and final project I have analyzed the interactions that users have with articles on the IBM Watson Studion platform. I have made recommendations to the users about new articles they may be intertested in.


## Getting Started

For this project I didn't create any virtual environment. I worked directly on Jupyter Notebook 

### Dependencies

For this project I installed Matplotlib for datavisualization, pandas numpy, scikit-learn tensorflow, and Jupyter

### Installation

Except the dependencies I did not install any other packages. I just used the import that were already in the template Recommendations_withIBM.ipynb
## Testing

As there were no virtual environnment you can work directly from the project directory. Just make sure to keep the same directory structure to preserve the paths

### Break Down Tests

I had to validate the data, checking for missing values, duplicates and inconsistencies in dataset. I hade to test the metrics details(precision, recal, mean Average) to assess recommendation. I also had to cross validate to test the popularity based articles.
I had a lot of debugging as I was stuck with the output format.

## Project Instructions

**1. Exploratory Data Analysis**: Before making recommendations, I start by exploring the dataset to understand its structure, identify patterns, and answer key questions. This initial analysis helps me gain insights that will guide the development of my recommendation system..  
**2. Rank-Based Recommendations**: I begin by identifying the most popular articles based on total interactions. Since there are no ratings available, I assume that the more interactions an article has, the more popular it is. These are the articles I would recommend to new users or those for whom I lack specific preferences.  
**3. User-User Collaborative Filtering**: To improve my recommendations, I analyze user behaviors to find similar users based on their interactions with articles. If users have engaged with similar content, I use that similarity to suggest articles they haven’t seen yet. This makes recommendations more personalized.  
**4. Content-Based Recommendations**: Since article content is available, I apply Natural Language Processing (NLP) techniques to cluster similar articles. By doing this, I can recommend related content based on what a user has previously engaged with, ensuring recommendations align with individual interests.
**5. Matrix Factorization**: For a machine learning approach, I use matrix factorization to build a recommendation model based on user-item interactions. This technique helps me predict new articles a user might enjoy by identifying latent features in the data. I also evaluate different methods to measure how well my system engages users and consider ways to refine it for better performance.


## Built With

* [Python](https://www.python.org/) – The core programming language used for data analysis and modeling.
* [Pandas](https://pandas.pydata.org/) (v2.2.3) – Data manipulation and structured data operations.
* [NumPy](https://numpy.org/) (v2.2.5) – Numerical computing and array operations.
* [Scikit-learn](https://scikit-learn.org/) (v1.6.1) – Machine learning algorithms and model training.
* [Matplotlib](https://matplotlib.org/) (v3.10.1) – Fundamental plotting and visualization.
* [Plotly](https://plotly.com/) (v6.0.1) – Interactive and dynamic visualizations.



## License

[License](LICENSE.txt)
