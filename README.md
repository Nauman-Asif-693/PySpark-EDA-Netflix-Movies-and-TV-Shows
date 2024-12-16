# PySpark EDA Netflix Movies and TV Shows
Using PySpark, an Exploratory Data Analysis (EDA) on Netflix Movies and TV Shows Dataset. This project falls under the *Asssignment # 3* of **CE408 - Cloud and Distributed Computing** by *Nauman Asif*.

## Overview
In this project, PySpark has been used to conduct EDA on the Netflix Movies and TV SHows Dataset. This analysis included insights such as:
- Data Preprocessing with PySpark.
- Looking into the Summary Statistics.
- The Distribution of the Dataset.
- Filteration of Movies and TV Shows.

## Dataset
The Dataset used for this Analysis is available on [kaggle.com](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies/data) and contains 2 different types of csv files.
- credits.csv
- titles.csv

The file used for this Analysis was the latter one because it contains details about the movies and tv shows and has columns such as:
- title
- type
- description
- release_year
- age_certification
- etc

## Pre-Requisites
- Windows 10 or 11
- User with Administrator privileges
- Access to Command Prompt or PowerShell
- WinRAR or 7-zip to extract .tar files
- Python 3.x
- Jupyter

## Setup Instructions
1. Go [jdk.java.net/archive/](https://jdk.java.net/archive/) and download OpenJDK 17.0.2
<img src = "images/Screenshot 2024-12-16 173101.png">
2. Extract the zip file and move it to C:\Java
3. Download latest Apache Spark release. [spark.apache.org/downloads](https://spark.apache.org/downloads.html)
4. The latest Spark version is selected by default. At the time of writing, the latest version is Spark 3.5.3 for Hadoop 3.3
5. Click the spark-3.5.3-bin-hadoop3.tgz download link.
<img src = "images/">
7. Select a location from a list of mirror servers to begin the download.
<img src = "images/">
8. Create a new Spark folder in the root of the C: drive using the following command:
   ```bash
   cd \ && mkdir Spark
   ```
   ```bash
   docker cp -L netflix_titles_eda.py spark-master:/opt/bitnami/spark/netflix_eda.py
   ```
