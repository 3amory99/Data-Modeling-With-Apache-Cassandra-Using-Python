# Data-Modeling-With-Apache-Cassandra-Using-Python

![cassandra](https://github.com/3amory99/Data-Modeling-With-Apache-Cassandra-Using-Python/blob/master/Images/1642449715141.png)

---

## Project Overview

The Sparkify Music Streaming Analysis project focuses on creating a NoSQL database and an ETL pipeline for Sparkify, a music streaming startup. Sparkify aims to analyze the data collected from its new music streaming app, covering songs and user activities.

---

## Project Description

In this project, we designed and built a NoSQL database using Apache Cassandra and created an ETL pipeline with Python to populate the database.

---

## Database Schema

The NoSQL database serves to answer specific queries related to song play data. It consists of tables for the following queries:

1. Retrieve artist, song title, and song length from music app history when sessionId = 338 and itemInSession = 4.
2. Retrieve artist name, sorted song list (by itemInSession), and user details (first and last name) for userId = 10 and sessionId = 182.
3. Retrieve all user names (first and last) from the music app history who listened to the song 'All Hands Against His Own'.

---

## ETL Process

The ETL (Extract, Transform, Load) process reads data from files in the data folder, denormalizes it to match the Apache Cassandra tables, and creates a new CSV file named `event_datafile_new.csv`.

---

## Project Files

This project comprises the following files and directories:

- `event_data`: Raw data collected from Sparkify's music streaming app.
- `Sparkify.ipynb`: Jupyter Notebook containing database creation and ETL code.
- `event_datafile.csv`: Denormalized CSV file derived from the `event_data`, ready for inserting data into Apache Cassandra tables.
- `Images`: Screenshot showing the data in the `event_datafile.csv` and `cqlsh` output.

---

## Output

![out1](https://github.com/3amory99/Data-Modeling-With-Apache-Cassandra-Using-Python/blob/master/Images/Screenshot%20from%202023-10-20%2016-06-05.png)
![out2](https://github.com/3amory99/Data-Modeling-With-Apache-Cassandra-Using-Python/blob/master/Images/Screenshot%20from%202023-10-20%2016-06-42.png)
![out3](https://github.com/3amory99/Data-Modeling-With-Apache-Cassandra-Using-Python/blob/master/Images/Screenshot%20from%202023-10-20%2016-08-35.png)
![out4](https://github.com/3amory99/Data-Modeling-With-Apache-Cassandra-Using-Python/blob/master/Images/Screenshot%20from%202023-10-20%2016-09-39.png)
![out5](https://github.com/3amory99/Data-Modeling-With-Apache-Cassandra-Using-Python/blob/master/Images/Screenshot%20from%202023-10-20%2016-10-13.png)


## How to Run

To execute the project, simply run the `Sparkify.ipynb` Jupyter Notebook to perform validation and sample queries.

Feel free to explore the dataset and analyze the music streaming behavior on Sparkify's platform.
