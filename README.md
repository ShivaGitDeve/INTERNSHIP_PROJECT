# INTERNSHIP_PROJECT
# Project Title: ("Gemini-Powered SQL Query Generator")

# Description:

### This project automates the process of generating and executing SQL queries against a dataset using natural language questions. It leverages Google's Gemini generative AI model to translate user queries into SQL and Python's sqlite3 library to interact with an SQLite database.    

# Key Features:

####   Schema Generation: Generates SQLite table schemas from dataset descriptions using the Gemini AI.    

#### Natural Language to SQL: Translates user's natural language questions into executable SQL queries.    

#### Automated Query Execution: Executes the generated SQL queries and provides the results.    

#### CSV Data Handling: Imports and processes data from CSV files using the Pandas library.    

#### SQLite Database Interaction: Creates and interacts with an in-memory SQLite database.    

# Technologies Used:

#### Python
#### Pandas
#### Google Gemini API
#### sqlite3
#### dotenv (for secure API key management)    
#### Setup Instructions:

# Install Dependencies:

## Bash

#### pip install pandas google-generativeai python-dotenv
## Configure API Key:

### Create a .env file in the project directory.

#### Add your Google Gemini API key to the .env file:

## API_KEY=YOUR_GEMINI_API_KEY
# Prepare your data:

#### Ensure your data is in a CSV file (e.g., Online Sales Data.csv).    
# Usage:

#### Run the main Python script.    
#### The script will prompt you to enter questions about your data in natural language.    
#### The script will generate and execute the SQL query and display the results.    
#### To exit, type 'q' and press Enter.    
# Example:

#### Type the Question related to the table
#### give me all the categories under product with count and total revenue
# Disclaimer:

#### Ensure you have a valid Google Gemini API key.
#### The accuracy of the generated SQL queries depends on the clarity of the user's questions and the complexity of the data.
