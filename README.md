# CS210_OW2_PROJECT
# Overwatch 2 Data Analysis Project

# Overview
This project analyzes Overwatch 2 gameplay data to gain insights into individual hero statistics. The data is collected from the OverFast API, which provides information on heroes, game modes, maps, and player statistics.

# Data Collection
The data is obtained by making requests to the OverFast API using the provided Python script. The API scrapes Blizzard pages and converts data into a more convenient format for analysis. The API uses FastAPI, Beautiful Soup, nginx as a reverse proxy, and Redis for caching.

# Data Analysis
The analysis focuses on key metrics such as games played, win rates, and K/D ratios for each hero. Various exploratory data analysis (EDA) techniques are applied, including filtering for high-win rate heroes, identifying top heroes based on specific metrics, and exploring correlations.

# Clustering
The project utilizes clustering algorithms to group heroes based on playstyle similarities. This helps identify most played heroes, heroes played earlier but not recently, and heroes rarely played.

## Future Work
Future improvements could involve obtaining additional data sources, exploring trends over time, and incorporating more player-specific variables. Advanced analytics techniques like machine learning may be explored for predictive analysis. Regular updates to the dataset will ensure relevance.

# How to Use
- Use the provided notebook cell to collect data from the OverFast API.
- Analyze the data using the provided Jupyter Notebook or customize the analysis based on your needs.

Feel free to explore and contribute to the project!

