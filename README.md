Movie Reviews Data - Machine Learning 

This project focuses on analyzing and merging two datasets: IMDB Superhero Movies and Metacritic Movies, both stored in MongoDB. The goal is to prepare the data for machine learning and gain insights into movie trends, especially focusing on 2020 releases. The project involves data retrieval, cleaning, merging, and exploratory data analysis using Python.

🛠️ Tools & Technologies Used

Programming Language:	Python
Database:	MongoDB
Libraries:	pymongo, certifi, pandas, tabulate, re, json,
Platform:	Jupyter Notebook

transformers, created by Hugging Face, provides pre-trained models for various machine learning tasks. It is compatible with PyTorch, TensorFlow, and Jax.

pandas is used for data manipulation and analysis. It’s especially useful for working with structured data. Pandas makes it easy to clean, transform, and analyze data quickly using a variety of built-in functions.

matplotlib is used for creating visualizations like plots, charts, and graphs. It gives you fine-grained control over how your data is presented visually.

numPy provides support for working with large, multi-dimensional arrays and matrices, along with a huge collection of mathematical functions to operate on these arrays efficiently.

tabulate is used to display data in a clean, readable table format.

certifi provides a bundle of trusted root certificates. These certificates are used to verify the security of SSL connections.

PyMongo is the official Python driver for MongoDB, which is a NoSQL database. It provides tools to interact with a MongoDB database from a Python application, allowing you to:

    Insert data
    Query data
    Update data
    Delete data
    Manage collections and databases

📥 Data Source

The data comes from two collections stored in MongoDB:

    Superhero Collection: Contains IMDB data for superhero movies.
    Metacritic Collection: Contains data scraped from Metacritic.
