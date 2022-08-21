# MAST30034 Project 1 README.md
- Name: Junbo Hu
- Student ID: 1038361

**Research Goal:** My research goal is tip analysis for trip data and weather conditions.

**Timeline:** The timeline for the research area is September to December in 2021

Directory
1. `data/raw`: Contains all the raw data files.
2. `data/curated`: Contains all the preprocessed data files.
3. `plots`: Output plots.

To run the pipeline, please visit the `notebook` directory and run the files in order:
1. `preprocess.ipynb`: This notebook will download the data needed and details all preprocessing steps and outputs it to the `data/curated` directory.
2. `analysis.ipynb`: This notebook is used to conduct analysis on the curated data.
3. `model.ipynb`: The script is used to run the model from CLI and the notebook is used for analysing and discussing the model.

If you want to do all of these in a single notebook, then use 'mast30034.ipynd'

Notice: Because the download API in NYC website is not works well amd the weather data is from database, they couldn't be downloaded directly using Python, please download map data and weather data in advance.
