# DSAN 6000 Project - Team 10

Mingqian Liu, Xinyu Li, Xin Xiang, Yanfeng Zhang

## Project Topic Summary

The Myers-Briggs Type Indicator, often abbreviated as MBTI, is a widely used psychological assessment tool designed to identify an individual’s personality preferences and tendencies. This project focuses on a multifaceted landscape of discussions within the MBTI community, especially on Reddit submissions and comments. This project employs diverse technical methodologies, from natural language processing to machine learning, to unravel patterns in user behavior, sentiment analysis, most common topics, and relationships between personality types and health-related data. The analysis aims to provide insights into the intricacies of communication, trends, and behavioral nuances within the MBTI community, shedding light on the diverse interests, linguistic preferences, and potential correlations between personality types and various aspects of online discourse.

## Update for Milestone 1 by 11/10/2023

Milestone 1 (EDA): will be tagged `v0.1-eda`. 

Link to the instruction: [Milestone 1: Define the questions and Exploratory Data Analysis](https://gu-dsan.github.io/6000-fall-2023/project/eda.html) 

Link to the published webiste: [Milestone 1: EDA](https://gu-dsan6000.github.io/fall-2023-reddit-project-team-10/eda.html)

**Updates:**
1. Add code notebook `project_eda.ipynb` for Milestione 1 to `code/EDA/` repo.
2. Add webpage file `ead.html` for  Milestione 1 to `website/` repo.
3. Add qmd file `ead.qmd` for Milestione 1 to `website-source/` repo.
4. Add processed 12 data files to `code/csv/` repo.
5. Add required visualizition output to `code/plots/` repo.
6. Add publish website `eda.html` to `docs/` repo.

**Notes**:
The exploratory data analysis (EDA) has been successfully completed by our team members. To review the division of labor and individual contributions, please refer to the **personal branches** of each team member on our repository, which are labeled with their respective names.

## Update for Milestone 2 by 11/17/2023

Milestone 2 (NLP): will be tagged `v0.2-nlp`

Link to the instruction: [Milestone 2: Natural Language Processing](https://gu-dsan.github.io/6000-fall-2023/project/nlp.html)

Link to the published webiste: [Milestone 2: NLP](https://gu-dsan6000.github.io/fall-2023-reddit-project-team-10/nlp.html)

**Updates:**
1. Add code notebook `nlp_linguistic.ipynb` for Milestione 2 to `code/nlp/` repo.
2. Add code notebook `nlp_sentiment.ipynb` for Milestione 2 to `code/nlp/` repo.
3. Add code notebook `nlp_topic.ipynb` for Milestione 2 to `code/nlp/` repo.
4. Add webpage file `nlp.html` for  Milestione 2 to `website/` repo.
5. Add qmd file `nlp.qmd` for Milestione 2 to `website-source/` repo.
6. Add processed 11 data files to `code/csv/` repo.
7. Add required visualizition output to `code/plots/` repo.
8. Add publish website `nlp.html` to `docs/` repo.

**Notes**:
The Natural Language Processing (NLP) has been successfully completed by our team members. To review the division of labor and individual contributions, please refer to the **personal branches** of each team member on our repository, which are labeled with their respective names.

## Update for Milestone 3 by 11/28/2023

Milestone 3 (ML): will be tagged `v0.3-ml`

Link to the instruction: [Milestone 3: Machine Learning](https://gu-dsan.github.io/6000-fall-2023/project/ml.html)

Link to the published webiste: [Milestone 3: Machine Learning](https://gu-dsan6000.github.io/fall-2023-reddit-project-team-10/ml.html)

**Updates:**
1. Add code notebook `ML_ARM.ipynb` for Milestione 2 to `code/ml/` repo.
2. Add code notebook `ML_prediction.ipynb` for Milestione 2 to `code/ml/` repo.
3. Add code notebook `ML_regression.ipynb` for Milestione 2 to `code/ml/` repo.
4. Add webpage file `ml.html` for  Milestione 2 to `website/` repo.
5. Add qmd file `ml.qmd` for Milestione 2 to `website-source/` repo.
6. Add processed data files to `code/csv/` repo.
7. Add required visualizition output to `code/plots/` repo.
8. Add publish website `ml.html` to `docs/` repo.

**Notes**:
The Machine Learning (ML) has been successfully completed by our team members. To review the division of labor and individual contributions, please refer to the **personal branches** of each team member on our repository, which are labeled with their respective names.

## Repository structure

The repository has the following structure:

```.
├── LICENSE
├── README.md
├── code/
├── data/
├── website/
└── website-source/
└── docs/
```
### Description

* The `code/` directory includes all of the scripts. There have a combination of Pyspark and Python notebooks, and one sub-directory per major task area.
* The `data/` directory contains all the data files.
* The `website/` directory where the final website will be built. Any website asset (image, html, etc.) will be added to this directory. 
* The `website-source/` directory is where we will develop the website using qmd. The outpur will render in `website/`.
* The `docs/` directory contains the website published to the Github page.
