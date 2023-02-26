# Books-Recommendation-System

This is a simple book recommendation system built using collaborative filtering techniques. The goal of this system is to suggest books to users based on their past reading history and the reading history of similar users.

## How it Works
The recommendation engine uses a matrix factorization algorithm to predict which books a user is likely to enjoy. It first creates a matrix of user ratings for each book, with missing ratings represented as zeros. It then factorizes this matrix into two lower-dimensional matrices representing the users and books, respectively. These matrices are then multiplied together to produce a prediction matrix, which contains the predicted rating for each user-book combination. The highest predicted ratings are then recommended to the user.

## Requirements
Python 3
pandas
numpy
scikit-learn
Tensorflow
Keras

## Usage
Clone the repository to your local machine.
Install the required packages using pip: pip install -r requirements.txt
Run the script: python recommendation_system.py
Enter a user ID to receive book recommendations.
