# FitBit Data Analysis and SQLite Integration

This project demonstrates how to analyze and convert multiple CSV files containing FitBit data into an SQLite database. The goal is to show the first line of each CSV file for comparison and then load the data into an SQLite database for further analysis.
The databse used can be found on Kaggle: https://www.kaggle.com/datasets/nurudeenabdulsalaam/fitbit-fitness-tracker-data

## Table of Contents

- [Project Overview](#project-overview)
- [Setup Instructions](#setup-instructions)

## Project Overview

This notebook performs the following steps:

1. Imports necessary libraries.
2. Reads and prints the first line of each CSV file to compare the structure.
3. Creates an SQLite database and loads the CSV data into tables.
4. Lists the names of all the tables created in the SQLite database.

## Setup Instructions

To run this notebook, you need to have Python and the required libraries installed. Follow the instructions below to set up your environment.

### Prerequisites

- Python 3.6+
- Pandas
- SQLite3
- Glob

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CSVtoSQL.git
   
