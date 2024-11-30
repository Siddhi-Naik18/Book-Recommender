# Book Recommender
## 📋 Project Overiew
The Book Recommender System is a Flask-based web application that uses preprocessed datasets and Pickle-stored models to offer book recommendations. It features a Top 50 Books section based on ratings and reviews and a Book Recommendation System that suggests the top 4 books related to a user's input. The app leverages Flask for backend logic and HTML/CSS for a responsive, user-friendly interface.
## 📊 Key Features
- Top 50 Books: Displays the most popular books based on user ratings and reviews, filtered to include only books with at least 250 ratings, sorted by average rating.
- Cosine Similarity-Based Book Recommendations: Utilizes the cosine_similarity function to find and recommend the top 4 books similar to a given input book based on their content and features.
- Efficient Data Management: The system uses pre-processed data and Pickle models to efficiently store and retrieve book information, including titles, authors, and cover images.
- Interactive UI: Offers an intuitive interface built with Flask, HTML, and CSS, allowing users to search for books and get recommendations instantly.
- Data Filtering and Sorting: Ensures only high-rated and popular books are shown in the Top 50 list, improving the relevance and quality of recommendations.
- Book Details: Each recommended book includes the title, author, and cover image, making the recommendations more engaging and informative.

## 🚀 Getting Started
# Prerequisites
- Python 3.x

- Install the requirements
``` 
pip install -r requirements.txt
``` 
# Running the Project
1. Clone this repository:
```
git clone https://github.com/Siddhi-Naik18/News_Scrapper.git
```
2. Run the command to open streamlit app:
```
streamlit run .\1_??_Home.py
```

## 🚀 Running the Project
1. Clone the repository
```
git clone https://github.com/Siddhi-Naik18/Book-Recommender-System.git
```
2. Install the required dependencies
Navigate to the project directory and install the dependencies using the requirements.txt file:
```
cd Book-Recommender-System
pip install -r requirements.txt
```
3. Run the Flask app
Start the app by running the app.py file:
```
python app.py
```

4. Access the app
Once the app is running, open your browser and go to:
`http://127.0.0.1:5000/` to view the Book Recommender System.



## 📂 Repository Structure
This repository contains the following files and directories:
- app.py: Main Flask application file where the routes and logic for the Book Recommender System are implemented.
- templates/: Directory containing HTML files for the frontend (index.html for the main page and recommend.html for the recommendation page).
- requirements.txt: Contains a list of Python dependencies required to run the project.
- Procfile: File used to run the application on Heroku.
- book-recommender-system.ipynb: Jupyter Notebook for exploring and analyzing the data.
- books.pkl: Serialized file containing book data used for recommendations.
- popular.pkl: Serialized file containing popular books data.
- pt.pkl: Serialized file containing pivot table data for book recommendations.
- similarity_scores.pkl: Serialized file containing similarity scores used in the recommendation engine.
- README.md: Provides an overview of the project, setup instructions, and how to run the application.

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/d6b0aeff-eca1-4751-a508-272fff40ae9b)

![image](https://github.com/user-attachments/assets/9f2c5bc0-e50e-4274-a159-db176b13c583)

![image](https://github.com/user-attachments/assets/1f66214b-d4de-4d96-964e-84791712b58f)

## 📝 Conclusion
This project showcases the implementation of a book recommendation system using machine learning techniques to suggest books based on user input. By utilizing Python libraries such as Pandas, Scikit-learn, and Flask, the application efficiently serves real-time book recommendations. The recommendation engine uses cosine similarity to identify the top 5 books related to a given book, providing users with personalized suggestions. The project highlights the use of data processing, machine learning models, and web development, making it a valuable tool for book discovery platforms, libraries, and reading applications.
