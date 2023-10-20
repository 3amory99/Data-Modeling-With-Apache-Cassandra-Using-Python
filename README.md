# Data-Modeling-With-Apache-Cassandra-Using-Python

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
- `event_datafile_new.csv`: Denormalized CSV file derived from the `event_data`, ready for inserting data into Apache Cassandra tables.
- `images`: Screenshot showing the data in the `event_datafile_new.csv`.

---

## How to Run

To execute the project, simply run the `Project_1B_Project_Template.ipynb` Jupyter Notebook to perform validation and sample queries.

Feel free to explore the dataset and analyze the music streaming behavior on Sparkify's platform.
