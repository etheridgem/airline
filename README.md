# Airline Insights
## Code Louisville Capstone Project 

### Overview

The purpose of this project is to analyze passenger satisfaction scores to uncover key insights and trends. This analysis aims to provide actionable recommendations for improving customer experience and driving business strategy for an airline company.

#### Scope
These datasets includes satisfaction scores from over 120,000 airline passengers, covering various aspects of their travel experience from 2020 to 2023. The data encompasses detailed information about each passenger, their flight, type of travel, and their evaluations of different factors like cleanliness, comfort, service, and overall experience. In combination with mock data.

#### Objectives
Customer Segmentation: Identify, characterize, and visualize different segments of passengers based on their satisfaction scores and travel patterns. 

Product Insights: Analyze which features of the travel experience (e.g., cleanliness, comfort, service) have the most significant impact on overall satisfaction. 

---

### Primary Files:
-This project uses two datasets: airline_passenger_satisfaction.csv and MOCK_DATA.csv

-This project uses SQL and Python using Jupyter Notebook: enriched_airlinepassenger.ipynb and airline_analysis.ipynb.

-Through enriched_airlinepassenger.ipynb, a database called 'airline_insights.db' will be created merging your primary datasets airline_passenger_satisfaction.csv and MOCK_DATA.csv to create a single dataset merged_data.csv which is hosted in the 'airline_insights.db'

-The data_dictionary explains definitions for the columns in the airline_passenger.csv and MOCK_DATA.csv 

---
## Installation
Before you begin, ensure you have met the following requirements:

- You have installed Python. This project was developed using Python 3.11.1. If you don't have Python installed or if you need to upgrade your current version, you can download it from the [official Python website](https://www.python.org/downloads/).
- You have installed Git, which is necessary to clone the repository. If you don't have Git installed, you can download it from the [official Git website](https://git-scm.com/downloads).

### Running the Program:

1. Fork the repository [repolink] (https://github.com/etheridgem/airline)
2. Clone the repository to your Github
3. Access the repository from your command line or preferred CMD software
4. Install a virtual environment. Below are directions are how to install per your machine:

Virtual Environment Commands
| Command | Linux/Mac | GitBash |

| Create | `python3 -m venv venv` | `python -m venv venv` |

| Activate | `source venv/bin/activate` | `venv/Scripts/activate.vat` |

| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |

| Deactivate | `deactivate` | `deactivate` |

1. Activate the virtual environment
2. Install the requirments.txt file to install necessary packages by running 'pip install -r requirements.txt'
3. Run the 'enriched_airlinepassenger.ipynb' first. A database called 'airline_insights.db' will be created.
4. Run the 'airline_analysis.ipynb' file to produce airline insights and visualizations.
---

### Features:
-Read Two Data Files: Load and process data from at least two different sources (e.g., CSV files).
    airline_passenger_satisfaction.csv and MOCK_DATA.csv

-Clean and Merge Data: Utilize pandas to clean and merge datasets, calculating new values where necessary.

-Data Visualization: Create at least three visualizations using Matplotlib or Seaborn to present insights from the data.

-Data Interpretation: Annotate your analysis with markdown cells in Visual Studio Code, ensuring clarity and coherence in your findings.

-Best Practices: Implement a virtual environment, and provide a clear data dictionary or README.md.

---

### Data Analysis Conclusions: