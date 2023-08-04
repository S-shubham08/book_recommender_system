# Book Recommender System

## Application Demo Pages:
### 1) Top 50 Books
![image](https://github.com/S-shubham08/book_recommender_system/assets/127888794/2c771de7-c227-4ae9-af97-6ae3c11543e3)

### 2) Search-based Recommendation
![image](https://github.com/S-shubham08/book_recommender_system/assets/127888794/ecca5e33-0928-4516-86ba-b78fc16639e4)

## Project Description
This project is a Book Recommender System that provides two functionalities:
- Top 50 Books: It displays a list of the top 50 books based on some popularity or rating metric.
- Search-based Recommendation: Given a user's search query (e.g., book title, author), the system recommends 5 relevant books.

The recommender system employs collaborative filtering and content-based techniques to make personalized book recommendations.

## Data Collection
Dataset Source - https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

## Project Strcuture
- /models: Stores the trained recommendation models.
- /templates: HTML files are present.
- app.py: Includes the Flask web application and API.
- requirements.txt: List of dependencies required to run the project.

## Install the required packages:
```
pip install -r requirements.txt
```

## Model Training
- The recommender system models are trained using the data in the Jupyter Notebook present in a directory.
- The trained models are saved in /models directory.

## Usage
1. Run the Flask application:
```
python app/app.py
```
2. Open your web browser and go to http://localhost:5000 to access the web application.
3. To see the Top 50 Books, click on the "Top 50 Books" section.
4. To get personalized recommendations based on your search, use the search bar to enter your query, and the system will display 5 relevant books.

