# Movie Recommendation System

## Overview
This project is a movie recommendation system built using neural networks on the MovieLens dataset.

It combines:
- collaborative filtering through user and movie embeddings
- content-based filtering through movie genre features

## Features
- preprocessing of ratings and movie metadata
- genre one-hot encoding
- user and movie ID mapping
- neural network model built with Keras
- evaluation using MAE and MSE

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## Project Structure
- `notebooks/` - original development notebook
- `data/` - dataset files if included

## Current Status
This repository currently contains the original project notebook.  
Next steps are to refactor the code into scripts, improve reproducibility, and add a simple app interface.

## Dataset
MovieLens dataset

## Future Improvements
- refactor notebook into modular Python files
- build a Streamlit app for recommendations
- improve evaluation with ranking metrics
- deploy a demo