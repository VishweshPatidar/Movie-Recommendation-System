# Movie Recommender System


This repository contains a Movie Recommender System project implemented using Python. The project includes a machine learning-based recommendation model and a Streamlit interface to provide user-friendly interaction.


## Features

- Recommends movies based on user input or similarity to a given movie.
- Interactive Streamlit web app for easy access.
- Built with machine learning for accurate recommendations.

## Repository Structure

- movie-recommender.ipynb   # Jupyter Notebook for development and experimentation
- app.py                   # Streamlit app for the recommender interface
- similarity.pkl           # Pre-trained similarity model (not uploaded due to file size)
- requirements.txt         # Required Python packages

## Installation

Clone the repository:

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name 
```

Install the required dependencies:

```
pip install -r requirements.txt
```


## Usage
## Run the Streamlit App
```
streamlit run app.py
```

Navigate to the URL provided in the terminal (usually http://localhost:8501) to interact with the app.

## Notebook
You can explore the model development process by opening the movie-recommender.ipynb notebook in Jupyter Notebook or JupyterLab:

```
jupyter notebook movie-recommender.ipynb
```

## Notes
- similarity.pkl: The trained similarity model file is required to run the app. Since it's too large to upload to GitHub, you can download or generate it locally. Make sure to place it in the root directory of this repository.
- To regenerate the similarity.pkl file, refer to the notebook for training instructions.

## Technologies Used
- Python
- Streamlit for the web interface
- Pandas and NumPy for data manipulation
- Scikit-learn for building the recommendation model

## Future Improvements
- Deploy the Streamlit app online for broader accessibility.
- Integrate additional datasets to improve recommendation quality.
- Optimize the similarity model for faster recommendations.

similarity.pkl is a big file and cannot be uploaded here. you need to generate your own similarity.pkl file by running the code
