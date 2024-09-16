# Netflix Movies and Tv Shows Data Analyst Using SQL

![Netflix_image](https://github.com/user-attachments/assets/515f5988-aedf-4795-969a-6cfd5e8be19b)

# Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using SQL. The goal is to extract valuable insights and answer various business questions based on the dataset. The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

# Advanced SQL Project for Netflix Data Analysis
## Introduction
This project showcases advanced SQL techniques used for analyzing and managing large-scale datasets similar to those handled by Netflix. It includes complex queries, performance optimization, and data modeling strategies.
## Features
- Complex SQL queries for user behavior analysis.
- Data modeling and schema design for large datasets.
- Performance tuning and optimization strategies.

# Dataset
The data for this project is sourced from the Kaggle dataset:

- **Dataset Link:** [Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

# Schema

## Schema

```sql
DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
```
