# Article Recommendation Engine

An algorithm to recommend articles to users based on rank, user similarity and Singular Value Decomposition (SVD).

## Description

The project analyzes the interactions that users have with articles on the IBM Watson Studio platform, and makes recommendations to them about new articles they might like. Below it's an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

![Screenshot](images/screenshot.png)

Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

You can become a part of their community, and get a better understanding of their data [by creating your own account on the platform here](https://classroom.udacity.com/nanodegrees/nd025/parts/fda1a44f-51b3-4093-8ee3-9e9a23e3bf81/modules/0675c6bd-f2c2-4711-a8f0-b5ce220f2b47/lessons/ed510bc1-30c8-42a0-9849-46d44291916f/concepts/b18d9903-a776-4e25-bbca-70109fa2f754).

The project is divided into the following tasks:

### 1. Exploratory Data Analysis

Explore the data to be worked with throughout the rest of the notebook.

### 2. Rank Based Recommendations

Find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

### 3. User-User Based Collaborative Filtering

Look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users and it's a step towards more personal recommendations.

### 4. Matrix Factorization

Build a machine learning approach to recommendations, through creating an user-item interactions matrix and decomposing it with SVD. This also gives an idea of how well the predictions of new articles an individual might interact with are.

### 5. Conclusion

Discuss which methods to use moving forward, and how to test how well the recommendations are working for engaging users.

## Dependencies

* Python 3.9.1
* NumPy 1.19.2
* Pandas 1.1.5
* Matplotlib 3.3.2
* Jupyter notebook 6.1.6

## Execute

1. Clone the git repository:

`git clone https://github.com/gabrieltempass/article-recommendation-engine.git`

2. Go to the project's directory.
3. Open the Jupyter notebook, with the command:

`jupyter notebook "notebook/Recommendations with IBM.ipynb"`


## Notebook

The Jupyter notebook, inside the notebook folder, contains the five parts detailed in the README description.

## Dataset

The original dataset was provided by IBM.