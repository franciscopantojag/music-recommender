# Music Recommender

A machine learning model to predict music preferences of a person based on their age and gender.<br/>
This project is the result of the "Python Machine Learning Tutorial" from [Programming with Mosh](https://www.youtube.com/c/programmingwithmosh).

## The problem

We need to predict which genre of music will prefer a person.

### Inputs

- Age
- Gender

## Solution

Build a model using machine learning to predict music preferences based on an input .csv music data file (/csv/music.csv). The model was built with Python using the [Jupyter](https://jupyter.org/) Notebook IDE, and some useful libraries.

### Steps followed to build the model:

1. Import the data
2. Clean the data
3. Split the data into Training/Test Sets
4. Create a model
5. Train the model
6. Make predictions
7. Evaluate and Improve

## Dependencies

- [Python](https://www.python.org/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Panda](https://pandas.pydata.org/)
- [Joblib](https://joblib.readthedocs.io/en/latest/)
- [Jupyter Notebook](https://jupyter.org/)

## Installation

Music Recommender requires [Python](https://www.python.org/) to run. (Tested on Python 3.9.1)<br/>
If you are using pip:

```sh
$ pip install -r requirements.txt
```

Otherwise, install the dependencies above. Start the jupyter server:

```sh
$ jupyter notebook
```

Open **music-recommender.iynb** and run the last cell.

## Usage

Choose person's gender (1 for men and 0 for woman) and age, and put it inside the predict method of the model:

```sh
predictions = model.predict([[<age>,<gender>]])
```
