# Music-Genre-Classifier

# Music Genre Classification and Analysis Using Spotify API

## Project Overview
This Jupyter Notebook is a comprehensive analysis tool for classifying and exploring various music genres using the Spotify API. It employs a combination of data collection, preprocessing, and machine learning techniques to build a robust model that can classify songs into genres such as pop, rock, jazz, classical, and hip-hop.


## How to Use it 
Update the credentials.txt with your own Spotify API credentials and launch the notebook.

## Key Features

### 1. Spotify API Integration
Uses the `spotipy` library to authenticate and fetch music tracks along with their metadata from Spotify, covering multiple genres.

### 2. Data Collection
Scripted processes to collect extensive data on tracks, including artist names, track IDs, and audio features like danceability, energy, and tempo.

### 3. Data Cleaning and Preprocessing
Implements techniques to clean and standardize the data, preparing it for effective machine learning.

### 4. Feature Engineering
Enhances the dataset with calculated features and transformations to improve model accuracy.

### 5. Model Training and Evaluation
Utilizes several machine learning algorithms (e.g., Logistic Regression, Random Forest, and SVM) to classify tracks into genres. Includes cross-validation and hyperparameter tuning to optimize model performance.

## Potential Applications

- Music recommendation systems.
- Audio feature analysis for academic research.
- Enhancing metadata for large music databases.

## Technologies Used

- Python for scripting.
- Pandas and NumPy for data manipulation.
- Scikit-learn for machine learning.
- Spotipy for interfacing with Spotify Web API.

## Challenges Addressed

- Handling authentication and data retrieval from Spotify.
- Managing large datasets and ensuring data quality.
- Building and tuning classifiers to accurately predict music genres based on audio features.


- PS: Analysis Notebook is only the analysis of my own dataset retrieved through the API.Each credential give unique dataset and thus unique results. 