# 🎬 Movie Recommendation System with MovieLens Dataset


## Table of Contents

-   [Technologies Used](#technologies-used)
-   [Description](#description)
-   [Objectives](#objectives)
-   [Notebooks Overview](#notebooks-overview)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Project Structure](#project-structure)
-   [Collaborators](#collaborators)
-   [License](#license)

---

## Technologies Used

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![LightFM](https://img.shields.io/badge/lightfm-%2300422e.svg?style=for-the-badge&logo=lightfm&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

---

## Description
This project is focused on building a movie recommendation system using the MovieLens dataset. The system leverages several machine learning techniques to provide personalized movie recommendations based on user preferences and past behaviors.

### Objectives
The main objective of this project is to develop and evaluate different recommendation algorithms, including collaborative filtering, matrix factorization, and hybrid approaches, using the MovieLens dataset. The specific steps include:

1. **Data Preprocessing**: Filtering and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding the dataset and its underlying patterns.
3. **Modeling**: Implementing various models like Pearson correlation, SVD, and LightFM for recommendations.
4. **Evaluation**: Assessing the performance of the models to identify the most effective approach.

---

## Notebooks Overview

1. **Dataframe_Filter.ipynb**:
   - This notebook is essential for preparing the dataset. It filters the raw data and generates a CSV file that is necessary for the subsequent models.
   - **Important**: You must run this notebook first to create the CSV file that will be used by the Pearson, LightFM, and SVD models.

2. **Exploratory_Data_Analysis.ipynb**:
   - Provides a comprehensive analysis of the dataset, including visualizations and insights into user ratings, movie genres, and other key aspects.

3. **NLP_Vectorizing.ipynb**:
   - Applies Natural Language Processing (NLP) techniques to vectorize textual data (e.g., movie descriptions) for use in hybrid recommendation models.

4. **Pearson_Correlation.ipynb**:
   - Implements a collaborative filtering model using Pearson correlation to recommend movies based on user similarity.

5. **SVD.ipynb**:
   - Uses Singular Value Decomposition (SVD), a matrix factorization technique, to predict user ratings for movies.

6. **New_Model_LightFM.ipynb**:
   - Develops a hybrid model using the LightFM library, combining both content-based and collaborative filtering approaches for recommendations.

---


> [!IMPORTANT]
> The project was developed and tested on Python 3.11.6

To run this project locally, follow these steps:

1. Clone the repository:
```sh
git clone https://github.com/jcrigoni/grand_ml_project
cd Movie-Recommendation-System
```
---

## Usage 

1. **Run the Dataframe_Filter.ipynb** notebook to create the necessary CSV file and used movie.csv and rating.csv on https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset  .
2. After running the first notebook, you can proceed to run the other notebooks to explore the data, build models, and generate recommendations.

> **TIP:** Some notebooks may take a while to run depending on the dataset size and complexity of the model. Please be patient!
---
## Project structure
```sh
📦 grand_ml_project/
├── 📁Data/
│   ├── 🐍Dataframe_Filter.ipynb
│   ├── 🐍Exploratory_Data_Analysis.ipynb
│   └── 🐍NLP_Vectorizing.ipynb
├── 📁Models/
│   ├── 🐍New_Model_LightFM.ipynb
│   ├── 🐍Pearson_Correlation.ipynb
│   ├── 🐍SVD.ipynb
│   ├── 🖼️banner.png
│   └── 📁Exported_Models/
│       └── 🗃️lightfm_recommendation_model.pkl
├── 📄README.md
├── 📄Project-Documentation_Movie_Recommendation_System_Kallel_Rigoni_Rodner.pdf
└── 📄.gitignore
```
---


## Colaborators

This project was developed by a collaborative team. Each member played a crucial role in the research, development, and analysis:

- **Mohamed Kallel**
- **Jean Christophe Rigoni**
- **Simon Pierre Rodner**
---



## License
This project is under the **CC BY-NC 4.0 License**. For more information, refer to the license file. <br/>
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
