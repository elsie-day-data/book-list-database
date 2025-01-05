# Book List SQL Database

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results Or Findings](#results-or-findings)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References or Resources](#references-or-resources)

### Project Overview

This data analysis project aims to provivde a list of my favorite books with associated ratings. By analyzing this information, I can keep track of 1) books I've read, and 2) ratings for further analytics exploration into things like themes and recommends.

<img width="1201" alt="Screenshot 2025-01-05 at 3 26 44 PM" src="https://github.com/user-attachments/assets/9208e178-2c4d-45b7-9654-46a938f68663" />

### Data Sources

Book Data: The primary dataset used for this was Perplexity as I asked for a list of trending non-fictional books in the US today.

### Tools 

- SQL Lite

### Data Preparation 

In the initial data preparation phase, I performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the book data to answer key questions such as:
1. What are three of my favorite books?
2. How would I rate each book?

### Data Analysis

Interesting code/features worked with:

```sql
CREATE TABLE books (id INTEGER PRIMARY KEY, name TEXT, rating INTEGER );
INSERT INTO books VALUES (1, "Be Ready When the Luck Happens: A Memoir", 3.5);
```

### Results or Findings

The analysis results are summarized as follows:
- No alalysis results, requires further questions to explore.

### Insights

It was interesting that building this data set required three phases of
1. Listing out the books and associated ratings
2. Creating a blank table to house the data
3. Inserting the book data into the blank table

### Recommendations

- Import more book data and explore if there is a correlation between book categories and ratings.

### Limitations
There were no limitations in this database. In the future I will use this section to detail any outliers or adjustments I had to make to the data to protect the accuracy of analysis I'm working to achieve.

### References or Resources
1. [How to Document Data Analysis Projects on GitHub the Right Way](https://www.youtube.com/watch?v=0N9xekdKCwk)
2. [Khan Academy](https://www.khanacademy.org/computing/computer-programming/sql/sql-basics/pc/challenge-book-list-database)
