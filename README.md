# Movie Prediction

I did this project to check out scikit learn and basic prediction algoritms

This project demonstrates the usage of the `cosine_similarity` function from the `sklearn` library for calculating similarity between movie ratings. It also involves data preprocessing techniques.

## Getting Started

To get started with this project, follow the instructions below:

1. Clone the repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Download the datasets from [https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) and put them in `/datasets/input/tmdb-movie-metadata/`.
4. Run the `model_generation.ipynb` notebook to generate the pickled models.
5. Run the `main.py` script to execute the movie prediction algorithm.

## Usage

The `main.py` script contains the logic for predicting movie ratings using the pickled model. You can modify the input data and experiment with different movie ratings to see the predictions.

## Data Preprocessing & generating the model

Before generating the pickle file, the input data goes through a preprocessing step. This step involves cleaning the data, handling missing values, and transforming the data into tokens. The tokens are then converted to vectors for the cosine similarity calculation. The similarity is then exported into a pickle file.

## Dependencies

This project requires the following dependencies:

- Python 3.x
- numpy
- pandas
- ast
- scikit-learn
- pickle

You can install the required dependencies by running `pip install -r requirements.txt`.
