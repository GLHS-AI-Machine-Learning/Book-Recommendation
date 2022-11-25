# Contributors:
Reyansh Bahl

# Overview
I created an item-based collaborative filtering system that recommends books based on the similarity between books calculated using the rating users have previously given. 

# Procedure
In this project, I used this [Kaggle dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset) and our school library dataset.

I filtered the Kaggle dataset to only include reviews for books that are available in our school library. I also applied some preprocessing and created a user interaction matrix. Finally, I created a k-nearest neighbors (KNN) that uses cosine similarity to find similar books to one that the user previously liked.

# How to run

After downloading the Kaggle dataset, move the files (`Books.csv`, `Ratings.csv`, `Users.csv`) to the same directory as this program. Also, download the spreadsheet titled "Fiction List of Books" from our Google Classroom as a CSV file. This contains books that are available in our school library. 

Upload `book_recommendation.ipynb` to DeepNote or any other Jupyter Notebook environment and run the code. You will need libraries `numpy`, `pandas`, and `sklearn`.
