# Recommendation engine with IBM

Yu Tao 04/12/2021

### Udacity Data Scientist Nanodegree Project 3

### Table of Contents

- 1. Installation
- 2. Project Motivation
- 3. File Descriptions
- 4. Instructions
- 5. Licensing, Authors, Acknowledgements

### Installation:
The program is running on Python 3, the following packages are needed: numpy, pandas, matplotlib and pickle.

### Project Motivation:
For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like.

### File Descriptions:

In the data folder, articles_community.csv and user-item-interactions.csv record the details of each article on the IBM Watson Studio platform and how the users interact with them.

Recommendations_with_IBM.html & Recommendations_with_IBM.ipynb include the data process details. Here, several recommendation methods were implemented.
- Rank Based Recommendations
- User-User Based Collaborative Filtering
- Matrix Factorization

project_tests.py is a test function (used together with all other files) that show the recommendations are functioning well.

### Instructions:
Run the jupyter notebook in Python 3 environment.

### Licensing, Authors, Acknowledgements
This project was completed as part of the Udacity Data Scientist Nanodegree.
The article data used to for different recommendations was provide by IBM Watson Studio.
