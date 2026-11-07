# Recipe Recommender: Feature Engineering and EDA

Prepares recipe and review data for a recommender system that suggests recipes based on a user's preferences and the recipe they are viewing. This project builds the features; it does not build the recommender itself.

## Notebooks

| Notebook | What it does |
| --- | --- |
| `01_FeatureExtractionPart01_final.ipynb` | Extracts nutrition values, builds per-100-calorie columns, standardizes them, converts tags to arrays, joins recipes to reviews, creates time-based features, saves to Parquet |
| `02_EDA-CompleteSolution_Final.ipynb` | Buckets and cleans numeric features such as `minutes` and years since submission |
| `03_FeatureExtractionPart02_final.ipynb` | Adds user-level average features and tag-level analysis (most and least rated tags) |

`Receipe_EDA_Assignment.pptx` summarizes the work.

## Data

Cleaned recipe and review data provided with the UpGrad assignment; not redistributed here.

## Stack

Python, pandas, Parquet
