# Music Recommender

This project is the result of a machine-learning course from [Programming with Mosh](https://www.youtube.com/c/programmingwithmosh).

## The problem

We need to predict which genre of music will prefer a person based on its age and gender.

## Solution

Build a model using machine learning to predict music preferences based on an input .csv music data file (/csv/music.csv). The model was built with Python using the [Jupyter](https://jupyter.org/) Notebook IDE, and some useful libraries.

### Steps

1. Import the data
2. Clean the data
3. Split the data into Training/test Sets
4. Create a model
5. Train the model
6. Make predictions
7. Evaluate and Improve

## Dependencies

- CSV file with data of people's preferences of music by age and gender.
- [Python](https://www.python.org/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Panda](https://pandas.pydata.org/)
- [Joblib](https://joblib.readthedocs.io/en/latest/)
- [Jupyter Notebook](https://jupyter.org/)

## Installation

Music Recommender requires [Python](https://www.python.org/) to run.

Install the dependencies, start the jupyter server

```sh
$ jupyter notebook
```

Open **music-recommender.iynb** and run the last cell

## Usage

Choose person's gender (1 for men and 0 for woman) and age to predict its possible prefered music genre, and put it inside the predict method of the model:

```sh
predictions = model.predict([[<age>,<gender>]])
```
