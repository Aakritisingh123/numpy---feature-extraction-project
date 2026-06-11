# Anime Data Analysis Project 🎌

## Overview

This project is a data analysis project built using **Python, Pandas, and NumPy**.

The main goal of this project is to clean anime dataset data, extract useful information from anime titles, and perform basic analysis to find insights from the dataset.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- DateTime
- python-dateutil

---

## Project Features

✅ Load anime dataset using Pandas  
✅ Data cleaning and preprocessing  
✅ Extract number of episodes from anime titles  
✅ Extract anime airing duration  
✅ Calculate total airing months  
✅ Find highest-rated anime  
✅ Find anime with maximum episodes  

---

## Project Workflow

### 1. Import Libraries

Used libraries:

```python
import numpy as np
import pandas as pd
```

---

### 2. Load Dataset

The anime dataset is loaded using Pandas:

```python
df = pd.read_csv('anime.csv')
```

---

### 3. Episode Extraction

Extracts the number of episodes from the anime title.

Example:

Before:

```
Naruto (220 eps)
```

After processing:

```
Episodes = 220
```

---

### 4. Extract Anime Time Period

Extracts the airing period from the title information.

Example:

```
Apr 2007 - Mar 2010
```

Converted into:

```
Months = 36
```

---

### 5. Data Analysis

### Highest Rated Anime

Finds anime with the highest score:

```python
df[df['Score'] == df['Score'].max()]
```

---

### Anime With Maximum Episodes

Finds anime having the most episodes:

```python
df[df['Episodes'] == df['Episodes'].max()]
```

---

## Project Files

```
Anime-Data-Analysis/
│
├── anime-analysis.ipynb
├── anime.csv
├── README.md
└── requirements.txt
```

---

## Installation

Install required libraries:

```bash
pip install pandas numpy python-dateutil
```

---

## How To Run

1. Download or clone this repository

```bash
git clone repository-link
```

2. Open the project folder

3. Start Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```
anime-analysis.ipynb
```

---

## Dataset

The project uses an anime dataset containing information such as:

- Anime Title
- Score
- Episodes
- Airing Period
- Other anime details

---

## Learning Outcomes

Through this project, I learned:

- Data manipulation using Pandas
- Data cleaning techniques
- Feature extraction
- Working with datasets
- Basic exploratory data analysis

---

## Author

Aakriti Singh