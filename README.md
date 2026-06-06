# data_management--case_study--spark-cassandra_in_ml-100k
Using spark and cassandra basic commands analyse ml-100k dataset.
This repository contains the code, analysis, and results for the MovieLens user behavior analysis assignment. The project uses Apache Spark for distributed data processing and Apache Cassandra for persistent data storage.

---

## 📋 Assignment Overview

The goal of this project is to analyze the MovieLens 100K dataset using Spark and Cassandra. The five core analytical tasks are:

1.  Calculate the average rating for each movie.
2.  Identify the top 10 highest-rated movies (with at least 20 ratings).
3.  Identify users who have rated at least 50 movies and determine their favorite genre.
4.  Find all users who are less than 20 years old.
5.  Find all users whose occupation is "scientist" and whose age is between 30 and 40 years old.

---

## 🛠️ Environment & Prerequisites

To reproduce the analysis, please set up the following environment:

| Component       | Version Used      |
|-----------------|-------------------|
| Python          | 3.10              |
| Apache Spark    | 3.5.8             |
| Apache Cassandra| 3.11.19           |
| Libraries       | `pyspark`, `cassandra-driver`, `pandas`, `matplotlib` |

---

## 🚀 How to Run

1.  Clone the repository:
    ```bash
    git clone https://github.com/[YOUR_GITHUB_USERNAME]/[YOUR_REPO_NAME].git
    cd [YOUR_REPO_NAME]
    ```

2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3.  Start your Spark and Cassandra server locally.

4.  Open and run the main notebook:
    ```bash
    jupyter lab ml-100k.ipynb
    ```

---

## 📊 Key Features & Workflow

1.  **Data Loading**: The dataset is loaded using RDDs and converted into Spark DataFrames.
2.  **Data Processing**: All five required analytical tasks are performed using Spark transformations and actions.
3.  **Persistence**: The results of each task are written to corresponding tables in Cassandra.
4.  **Validation**: The stored data is verified using native Cassandra queries.
5.  **Visualization**: The top 10 highest-rated movies are visualized using a bar chart.

---

## 📝 Results Summary

All five tasks have been successfully completed, and the results are stored in tables:
- `output1`
- `output2`
- `output3`
- `output4`
- `output5`

Visualization include:
- `top10_movies`
- `most_popular_base_on_rate`
- `age_distribution`
- `occupation`

---

## 📄 License

This project is for educational purposes only.
```
