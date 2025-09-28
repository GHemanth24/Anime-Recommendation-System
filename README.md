Anime Content-Based Recommendation System

This project implements a content-based anime recommendation system using metadata and similarity techniques. It provides recommendations based on anime titles, genres, and other features. The project includes both a Jupyter Notebook for experiments and a Streamlit web app for an interactive interface.

📂 Project Structure
ANIME_CONTENT_BASED/

│── Main.ipynb         # Jupyter Notebook for exploration and testing

│── app.py             # Streamlit app for recommendations

│── dataset_1.csv      # Anime dataset (metadata)

│── README.md          # Project documentation

⚙️ Requirements

Make sure you have Python 3.8+ installed. Install the required dependencies using:

pip install -r requirements.txt


If you don’t have a requirements.txt, the main dependencies are:

pip install streamlit pandas scikit-learn numpy

🚀 Running the Project
1. Explore in Jupyter Notebook

Run the notebook to understand preprocessing and recommendation logic:

jupyter notebook Main.ipynb

2. Run the Streamlit App

Start the web app with:

streamlit run app.py


Then open the link shown in your terminal (default: http://localhost:8501
).

📊 Dataset

dataset_1.csv contains anime information used for recommendations.

It includes metadata such as titles, genres, and descriptions.

This data is processed to compute similarity scores for generating recommendations.

🧠 Methodology

Data Preprocessing – clean and structure anime metadata.

Feature Extraction – use text/genre features for similarity.

Content-Based Filtering – compute similarity using cosine similarity.

Recommendation – return top N similar anime for a given input.

🎯 Features

Search anime by title.

Get top-N recommendations based on similarity.

Interactive web interface built with Streamlit.

📌 Future Improvements

Add collaborative filtering.

Integrate deep learning models for embeddings.

Deploy online using Streamlit Cloud / Hugging Face Spaces.
