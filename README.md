# League-of-Legends-LoL-Match-Analysis-using-PySpark-6GB-Dataset
League of Legends (LoL) Match Analysis using PySpark | 6GB Dataset
This repository contains an analysis of League of Legends (LoL) match data using PySpark. The analysis is performed on a large-scale dataset of approximately 6GB in size. The dataset includes information about matches, champions, items, and various statistics.

Dataset
The dataset used in this analysis consists of LoL match data, which includes information about individual matches, such as the participating teams, champions selected by each player, item builds, match outcomes, and more. The dataset size is approximately 6GB.

Analysis
The analysis performed in this project utilizes PySpark, a powerful framework for big data processing and analysis. The PySpark framework enables efficient processing and analysis of the large-scale LoL match dataset.

Key components of the analysis include:

Calculating champion win rates based on match outcomes
Determining ban rates for champions
Analyzing item synergies and their impact on win rates
Examining pick rates for champions and items
Investigating champion synergies and their win rates
Exploring country-specific champion win rates
Repository Structure
The repository is organized as follows:

data/: Folder containing the large-scale dataset (not included in the repository due to its size)
analysis.ipynb: Jupyter Notebook containing the PySpark code for the analysis
Riot_match_collector.ipynb: Jupyter Notebook containing the code to download the data set from RIOT api
items.json: JSON file containing information about LoL items
champions_with_highest_win_rate_per_country.csv: CSV file containing champions with the highest win rates per country
item_synergies.csv: CSV file containing item synergies and their win rates
item_pick_rate.csv: CSV file containing item pick rates
item_win_rate.csv: CSV file containing item win rates
champion_synergies.csv: CSV file containing champion synergies and their win rates
champion_pick_rate.csv: CSV file containing champion pick rates
champion_ban_rate.csv: CSV file containing champion ban rates
champion_win_rate.csv: CSV file containing champion win rates
Usage
To replicate the analysis or explore the results, follow these steps:

Obtain the LoL match dataset y executing the Riot_match_collector.ipynb Jupyter Notebook (approximately 6GB in size) and place it in the data/ folder.
Install the required libraries and dependencies as specified in the requirements.txt file.
Execute the code in the analysis.ipynb Jupyter Notebook to perform the analysis.
Explore the generated CSV files to access the results of the analysis.
