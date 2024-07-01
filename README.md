# 2024 Lok Sabha Election Analysis

## Overview
This repository contains a comprehensive analysis of the 2024 Lok Sabha election results in India. The project includes data scraping for each state, followed by in-depth analysis to provide insights into voting patterns, party performances, and regional variations across the country.


## Web Scraping
I performed web scraping for each and every state in India to ensure comprehensive coverage of the 2024 Lok Sabha election results. The scraping process involved:
- Automated collection of data from official state election websites
- Extraction of key information such as candidate names, party affiliations, vote counts, and constituencies
- Data validation and error checking to ensure accuracy
- Compilation of state-wise data into a unified dataset for analysis

## Key Insights
1. Top performing candidates
2. Major party performance
3. Winning margins analysis
4. State-wise voter turnout
5. NOTA (None of the Above) impact
6. Postal votes contribution
7. Candidates with lowest votes
8. Party-wise seat distribution
9. Regional party dominance
10. Voter turnout variations

## Getting Started
To reproduce this analysis:
1. Clone this repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the data scraping scripts: `python src/run_all_scrapers.py`
4. Run the main analysis script: `python src/main_analysis.py`

## Data Sources
The data used in this analysis was scraped from official state election websites and the Election Commission of India's portal. 

## Tools Used
- Python 3.8+
- Beautiful Soup and Requests for web scraping
- Pandas for data manipulation
- Matplotlib and Seaborn for visualizations

## Contributors
-Subham Sharan

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Election Commission of India and state election portals for providing the raw data

## Contact
For any queries regarding this analysis or the data scraping process, please open an issue in this repository or contact ss9125@srmist.edu.in.
