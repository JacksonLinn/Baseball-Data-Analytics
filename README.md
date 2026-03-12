# Baseball Data Analytics

This project analyzes historical Major League Baseball data using the **Lahman 2014 baseball database**. The goal of the project is to explore player performance, team statistics, and trends in baseball using SQL and Python-based data analysis.

## Dataset

The analysis uses the **Lahman Baseball Database (2014 version)**, which contains historical MLB statistics including:

- Player batting statistics
- Pitching performance
- Team records
- Game outcomes
- Historical player and team information

The database is stored as a SQLite file:

```
lahman2014.sqlite
```

## Technologies Used

- Python
- SQLite
- Pandas
- NumPy
- Jupyter Notebook

## Project Structure

```
baseball-data-analytics
│
├── Project2.ipynb        # Main analysis notebook
├── lahman2014.sqlite     # Baseball statistics database
└── README.md             # Project documentation
```

## Analysis Overview

The notebook performs several types of baseball data analysis, including:

- Querying baseball statistics using SQL
- Analyzing player and team performance
- Exploring trends in batting and pitching data
- Performing data cleaning and transformations
- Visualizing baseball statistics using Python libraries

## Key Questions Explored

- Which players have the highest batting averages historically?
- How do team payrolls relate to team performance?
- What statistical patterns appear across seasons?
- Which players show consistent offensive performance?
  
## Running the Project

1. Clone the repository

```
git clone https://github.com/YOURUSERNAME/baseball-data-analytics.git
```

2. Navigate into the project folder

```
cd baseball-data-analytics
```

3. Open the notebook

```
jupyter notebook Project2.ipynb
```

Make sure the `lahman2014.sqlite` database file is in the same directory as the notebook.

## Author

Jackson Lin  
University of Maryland – Computer Science
