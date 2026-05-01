# ics604-final-project

## Analyzing Anime Trends in 2018 and Viewer Behaviors


This project analyzes anime trends, adaptation success, and viewer behavior using MyAnimeList datasets from 2018 and 2023. It identifies top 50 TV anime in 2018 and their source material, examines the relationship between manga scores and their anime adaptation scores, and explores gender-based differences in shounen and shoujo viewing patterns. Methods include data preprocessing, regression analysis, correlation, bootstrap confidence intervals, and hypothesis testing with effect size evaluation. Results show a strong positive relationship between manga scores and their anime adaptation scores, minimal gender differences in shounen viewing, and a large gender difference in shoujo consumption.

### Dataset Links:
- AnimeList.csv: https://www.kaggle.com/datasets/azathoth42/myanimelist?select=AnimeList.csv
- UserAnimeList.csv: https://www.kaggle.com/datasets/azathoth42/myanimelist?select=UserAnimeList.csv
- UserList.csv: https://www.kaggle.com/datasets/azathoth42/myanimelist?select=UserList.csv
- anime.csv: https://www.kaggle.com/datasets/andreuvallhernndez/myanimelist/data?select=anime.csv
- manga.csv: https://www.kaggle.com/datasets/andreuvallhernndez/myanimelist/data?select=manga.csv

Please download the datasets from the links above. 
To download the datasets you will need to login into Kaggle.

### Instructions to Run the Code on Google Colab
- Please use Google Colab Pro to run the Jupyter Notebook.
- In your Google Drive, please create a folder named "anime_data" in your My Drive. 
- Upload all five dataset ZIP files into the "anime_data" folder.
- When running the Jupyter Notebook, some of the cells may take 15 minutes or more, depending on the runtime hardware. 
- For faster performance, use the G4 GPU hardware accelerator. The longest cell runtime observed was around 5 minutes.
- If you are using the free version of Google Colab, you may also use the v5e-1 TPU hardware accelerator.
- Run the notebook cells from top to bottom. 