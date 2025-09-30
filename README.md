# datafun-06-eda
Data Analytics Fundamentals Week 6/7 Project


## Creating the Repo / Repeatable Workflow
1. Created `datafun-06-eda` in GitHub
2. Copied the URL from GitHub and cloned to my personal machine using the following code:
```shell
cd C:\Repos
git clone (URL)
```
3. Created `.gitignore` and `requirements.txt` files
   1. Implemented contents from example repo by Dr. Case (original example Repo)
4. Add - Commit - Push
5. Created a .venv with the following code:
```shell
py -m venv .venv
.\.venv\Scripts\activate
```
6. Installed Dependencies with the following code:
```shell
pip install --upgrade setuptools wheel
pip install --upgrade -r requirements.txt
```
7. Add - Commit - Push
8. Added other requirements from Dr. Case's Week 6 example repo
   1. These were mainly packages we will need to be able to use.

## Creating the Jupyter Notebook
1. Created a file while in VS Code called `karlidean_eda.ipynb` to run my EDA project with.
2. Add - Commit - Push
3. Annotated the notebook by writing titles, bylines, and purpose statements
4. Imported packages like numpy and pandas using the following code:
```shell
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import numpy as np
```
5. Add - Commit - Push

## Choosing My Data Set
I chose a data set from the NCAA for this project. I went to the link below and input the 2024-2025 Division II Volleyball season as the data I wanted to pull. These should be the season stats for each team.
[NCAA Division II Season Stats (2024-2025)](https://web1.ncaa.org/stats/StatsSrv/rankings?doWhat=archive&sportCode=WVB)
- Unfortunately, each stat was given to me as separate tables within a CSV, so I merged them all together in Excel to create the dataset I will be working with.
- In this link, you will only need to follow the path:
  - Select "2024-2025" > View
  - Select Division II > Through Games 12/14/2024 (Final)
  - Select "All Statistics" in the Team Category
  - Export to CSV "Show Report"
1. Once I found and compiled my dataset, I created a data folder in my repo.
   1. I then proceeded to add my dataset CSV to this repo.
   2. This is Option 1 (the safe way) from the directions. I believe this is easier for an internal DataFrame document.
2. Added the CSV to my Jupyter Notebook
3. Used the head, describe, shape, and dtypes functions to start my initial analysis
4. Add - Commit - Push

## Completing the Project
1. Outlined my project to define where I want to go (process-wise)
   1. This was the same outline I used for the Week 4 project
   2. Up to this point I have completed the "Descriptive Statistics" section
2. Add - Commit - Push