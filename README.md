# P153112-STQD6324-ASGMT3
Assignment 3 for STQD6324 using MongoDB and Spark2

# MovieLens 100k Analysis using MongoDB & Spark2
 
**Dataset:** [MovieLens 100k](https://grouplens.org/datasets/movielens/)  
**Tools Used:** MongoDB, Spark2 (PySpark), Python

---

## Project Overview

This project answers 5 analytical questions based on the MovieLens 100k dataset using Spark2 and MongoDB. All processing is done in PySpark via Spark SQL, with data stored and queried from MongoDB collections.

The Jupyter notebook includes:
- Data insertion steps (`u.user`, `u.data`, `u.item`, `u.genre`)
- Spark queries using MongoDB as the data source
- Outputs shown for each question 
- Comments + markdowns explaining each step

---

## Questions Answered

1. **Average rating for each movie**
2. **Top 10 movies with highest average rating**
3. **Users who rated at least 50 movies & their favourite genre**
4. **Users under 20 years old**
5. **Scientists aged 30–40 years old**

All answers are presented using PySpark DataFrames and MongoDB collections.

---

##  Submission Contents

- `STQD6324_Assignment3.ipynb` → Main notebook (with code + outputs + explanation)
- No raw data or scripts included, as data is loaded from local MongoDB during runtime.

---

## How to Run

This notebook is designed to run in a Spark2 + MongoDB setup via HDP Sandbox.  
Make sure:
- MongoDB is running locally (`localhost:8888`)
- `mongo-spark-connector` JAR is included during `spark-submit` if running outside Jupyter

---

> **Created by Afiqah Khairuna @ Universiti Kebangsaan Malaysia**
