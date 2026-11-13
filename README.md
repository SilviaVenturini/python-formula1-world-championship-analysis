# 🏎️ Formula 1 World Championship – Drivers and Constructors Analysis (2008)
## 📌 Project Overview
This project focuses on analyzing the results of the 2008 Formula 1 World Championship using Python.

The analysis is developed within a business scenario in which F1 Analytics, a company specialized in Formula 1 performance analysis, aims to evaluate individual driver performances and constructor results throughout the season.

Using a dataset containing race results, drivers, constructors, and Grand Prix locations, the project implements a set of Python functions to calculate championship points, identify race victories and podium finishes, and generate drivers' and constructors' standings.

The main objective is to transform raw race data into structured information that supports the evaluation and comparison of driver and team performances.

## 🗂️ Dataset
The project uses the formula1_data.csv dataset, containing information about the 2008 Formula 1 World Championship.

**Dataset Source:** Formula 1 Dataset

**Data Format:** CSV file.

**Main Features:**

- **Driver:** Name of the racing driver.
- **Team:** Constructor or racing team represented by the driver.
- **Race:** City where the Grand Prix took place.
- **Country:** Country hosting the Grand Prix.
- **Position:** Driver's finishing position, ranging from 0 to 8. A value of 0 indicates that the driver did not finish among the top eight positions and therefore did not score points.

## 🎯 Project Objectives
The main objectives of the project were:

- Analyze individual driver performances throughout the 2008 championship.
- Calculate the total points accumulated by each driver.
- Identify the number of race victories and podium finishes.
- Generate the final drivers' standings.
- Export drivers' championship results into a text file.
- Calculate the total points accumulated by each constructor.
- Generate a constructors' performance summary.

## 🏆 Formula 1 Scoring System
The 2008 Formula 1 World Championship used the following points allocation system:

| Finishing Position | Points Awarded |
|:---:|---:|
| 1st | 10 |
| 2nd | 8 |
| 3rd | 6 |
| 4th | 5 |
| 5th | 4 |
| 6th | 3 |
| 7th | 2 |
| 8th | 1 |
| 9th or lower | 0 |

## 🛠️ Tools & Techniques
- Python
- Google Colab
- CSV Module
- File Handling
- Python Functions
- Dictionaries
- Lists
- Loops and Conditional Statements
- Data Aggregation
- Data Processing
- Text File Generation
  
## 📂 Project Workflow
## 1. Individual Driver Performance Analysis
The first function, *analyze_driver_performance()*, calculates the performance statistics of a specific driver.

The function receives a driver's name as input and returns a list containing three key metrics:

- **Total Points:** Sum of all championship points accumulated throughout the season.
- **Total Wins:** Number of races won (1st place finishes).
- **Total Podiums:** Number of races finished in the top three positions.

The function uses a dictionary to associate each finishing position with its corresponding championship points.

If the specified driver is not found in the dataset, the function returns an empty list and displays an informative message.

## 2. Drivers' Final Standings
The second function, *generate_final_standings()*, calculates the total championship points accumulated by each driver.

Key activities:

- Extracting all unique driver names from the dataset.
- Calculating each driver's total points using the previously implemented function.
- Storing driver names and their corresponding points in a dictionary.
- Exporting the results into a text file named Drivers_Standings_2008.txt.

The generated file contains the drivers' names and their respective championship points.

## 3. Constructors' Standings
The third function, *constructors_standings()*, calculates the total championship points accumulated by each constructor.

Key activities:

- Reading the previously generated drivers' standings file.
- Associating each driver with their corresponding constructor.
- Grouping drivers according to their teams.
- Summing the individual points earned by drivers representing the same constructor.
- Storing the final results in a dictionary.

This analysis provides an overview of constructor performance based on the combined results of their drivers.

## 💡 Business Value
This project demonstrates how Python can be used to transform raw sports data into structured performance information.

The implemented functions provide several analytical benefits:

- **Driver Performance Evaluation:** Enables the comparison of individual drivers based on points, victories, and podium finishes.
- **Constructor Performance Analysis:** Provides insights into team performance by aggregating the results of their drivers.
- **Automated Reporting:** Generates a structured text file containing drivers' championship results.
- **Data Processing Automation:** Reduces the need to do calculations manually by using Python functions that can be used multiple times.
- **Decision Support:** Provides structured information that can support performance analysis and comparisons across drivers and constructors.

## 🎓 Conclusion
This project demonstrates the application of Python programming techniques to the analysis of Formula 1 championship data.

Through the implementation of custom functions, dictionaries, loops, conditional statements, and file handling operations, the project processes race results and calculates individual and team performance metrics.

The analysis provides a clear way to evaluate the drivers' results and the teams' performance during the 2008 Formula 1 World Championship.

Overall, this project strengthened my practical skills in Python programming, data manipulation, data aggregation, and automated report generation.

## 📁 Repository Contents
- **[Analysis_of_the_Formula_1_World_Championship_Drivers.ipynb](Analysis_of_the_Formula_1_World_Championship_Drivers.ipynb):** Google Colab notebook containing the complete Python implementation and the three analytical functions.
- **[formula1_data.csv](formula1_data.csv):** Source dataset containing the 2008 Formula 1 race results.
- **[Drivers_Standings_2008.txt](Drivers_Standings_2008.txt):** Generated text file containing the drivers' championship points.

## 📬 Contact
- **Silvia Venturini**
- [LinkedIn](https://www.linkedin.com/in/silvia-venturini92/)
- **Email:** silvia.venturini92@hotmail.com
