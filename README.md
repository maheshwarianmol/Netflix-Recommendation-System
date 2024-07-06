# Netflix-Recommendation-System
A Netflix recommendation system project focused on data cleaning, preparation, and analysis to improve movie recommendations using TMDB data.
Here is a draft for your README.md based on the content I could extract from your project file:

---

# Netflix Movie Recommender System

## Project Overview
This project aims to develop a Netflix Movie Recommender system using various machine learning techniques and data preprocessing methods. The project includes data cleaning, text mining, and the application of recommendation algorithms to suggest movies to users based on their preferences.

## Libraries Used
- Pandas
- Numpy
- Scikit-learn
- NLTK
- Matplotlib

## Cleaning DataFrame
This section is responsible for cleaning the dataset:
1. Checking for null data and rows with 0 runtime.
2. Filling in missing runtime and overview information using an API key from the TMDB website.
3. Creating functions to extract specific data from multiple columns.
4. Converting text to lowercase, removing spaces, and combining relevant data into new columns.
5. Renaming and dropping columns for clarity.
6. Creating a new dataframe with the cleaned data.
7. Joining the "tag", "tag_genres", and "tag_ppl" lists into single string values for further processing.

## Text Mining Preprocessing Techniques

This section includes text mining processing techniques such as:
- Removing punctuation
- Tokenization
- Stop words removal
- Lemmatization

## Recommendation Algorithm
The recommendation algorithm used in this project includes:
1. **Content-based Filtering:** Recommends movies based on the similarity of their content to movies the user has previously enjoyed.
2. **Collaborative Filtering:** Recommends movies based on the preferences of other users who have similar tastes.

## Evaluation
The performance of the recommender system was evaluated using metrics such as:
- Precision
- Recall
- F1 Score

## Conclusion
The Netflix Movie Recommender System successfully provides personalized movie recommendations based on user preferences and viewing history. Future improvements could include incorporating more sophisticated algorithms and additional data sources.

## How to Use
1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter notebook to train the model and generate recommendations.






