# M5 World Championship Statistics

## Overview

This repository contains Python scripts for scraping and analyzing statistics from the M5 World Championship, the final event of the MLBB 2023 Competitive Season organized by Moonton. The provided statistics include hero picks, bans, win rates, and team preferences, offering valuable insights for MLBB players.

## Contents

1. **Scraping Script: `m5_world_championship_scraper.py`**
    - **Libraries Used:** Requests, BeautifulSoup, Pandas, Matplotlib
    - This script fetches data from [Liquipedia](https://liquipedia.net/mobilelegends/M5_World_Championship/Statistics) and extracts information on hero performance during the M5 World Championship. The data is then stored in a CSV file (`m5_world_championship_stats.csv`).

2. **Team Preferences Script: `m5_world_championship_team_hero.py`**
    - This script extracts information from the last column of `m5_world_championship_stats.csv` to determine which teams played each hero during the tournament. The data is then stored in a separate CSV file (`m5_world_championship_hero_teams.csv`).

## Instructions

### Scraping Script
1. Run `m5_world_championship_scraper.py` to fetch and process the M5 World Championship statistics.
2. Ensure you have the required libraries installed (`requests`, `beautifulsoup4`, `pandas`, `matplotlib`).

```bash
pip install requests beautifulsoup4 pandas matplotlib
```

3. The script will create a CSV file (`m5_world_championship_stats.csv`) with detailed statistics.

### Team Preferences Script
1. Run `m5_world_championship_team_hero.py` to extract team preferences based on the hero data.
2. The script utilizes the last column of `m5_world_championship_stats.csv` to generate a new CSV file (`m5_world_championship_hero_teams.csv`) containing hero-team relationships.

## Data Files

1. **`m5_world_championship_stats.csv`:** Contains detailed statistics on hero picks, bans, win rates, and team preferences during the M5 World Championship.

2. **`m5_world_championship_hero_teams.csv`:** Presents information on which teams played each hero, including the number of games played, wins, and losses.

## Data Visualization

The `m5_world_championship_stats.csv` file provides comprehensive statistics, and users can utilize tools like Python and Jupyter notebooks to create custom visualizations based on their preferences.

Feel free to explore and analyze the data to gain insights into hero performance and team preferences during the M5 World Championship!

For any questions or issues, please open an [issue](https://github.com/valpaulo/M5-World-Championship-Hero-Statistics/issues).

Happy analyzing!