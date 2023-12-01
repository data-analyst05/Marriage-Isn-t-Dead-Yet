# Marriage Isn't Dead Yet: Analyzing Marriage and Divorce Trends in America

## Overview
"Marriage Isn't Dead Yet" is a data-driven project aimed at analyzing the trends in marriage and divorce in the United States. This project challenges common perceptions about marriage and divorce, providing a nuanced understanding based on statistical data.

## Objectives
- To explore historical and current trends in marriage and divorce rates in the U.S.
- To understand the impact of demographic changes on marriage rates.
- To analyze state-specific marriage and divorce statistics, with a focus on notable cases like Nevada.

## Methodology
- **Data Sources**: Utilized CDC csv data loaded into an SQLite database, read as JSON in JavaScript for real-time analysis.
- **Data Processing**: Implemented web scraping using Beautiful Soup and request library for live data collection. The data is then stored, categorized, and queried from a SQL database.
- **Visualization Tools**: Employed D3.js and Plotly for dynamic and interactive data visualization. Granim.js is used for aesthetic enhancements.

## Key Findings
- The number of married couples in the U.S. has increased, likely due to population growth rather than an increased propensity for marriage.
- The divorce rate in the U.S. has been declining since the 1990s, contrary to popular belief.
- Nevada has the highest rate of marriage and divorce, potentially due to its lenient laws.

## Technologies Used
- **Frontend**: JavaScript, HTML5, CSS3, Bootstrap
- **Backend**: Flask for API development
- **Data Visualization**: D3.js, Plotly
- **Database**: SQLite
- **Data Scraping**: Beautiful Soup, requests

