# The Lyrical Empiricals - Capstone Project

### Dataset
We obtained our dataset from Kaggle (https://www.kaggle.com/datasets/neisse/scrapped-lyrics-from-6-genres?select=artists-data.csv)
The dataset originally had over 150,000 songs across 4,168 unique artists.
The dataset includes song name, artist name, genres, and lyrics.
For our project, however, we decided to use songs covering 32 American artists with the most songs. After filtering to these artists, we have a little over 1400 songs across 32 artists, each with 300 or more songs.

### How to run our code:
A. Data Cleaning - 
Once the Data has been downloaded, save the data set containing the lyrics as "lyrics-data.csv". Then run 'Data Cleaning.ipynb'

B. Exploration - 
After running the Data Cleaning notebook, place the output file (lyrics_clean.csv) into a subfolder named 'data'. Then run 'Exploration.ipynb'

C. Clustering - 
Make sure lyrics_clean.csv is present in the 'data' subfolder. Then run 'Genre Clusters.ipynb'

C. Topic Modeling

D. Generative Model 
There are 4 notebooks in the Generative_Model folder: https://github.com/kennyta0204/Capstone-Project/tree/main/Generative_Model
Run them in order 





### Requirement.txt 

pandas==1.3.4
nltk==3.6.5
matplotlib==3.5.1
numpy==1.21.5
scikit-learn==1.0.1
tensorflow==2.7.0
language_tool_python==2.6.1
keras_tuner==1.3.5
