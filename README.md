Data Validation Pipeline (ETL)
This script performs a simple Extract, Transform, Load (ETL) process using Python. It fetches placeholder data from an external API, processes it to add metadata, and saves the final result to a CSV file while maintaining an execution log.
Features
Extract: Fetches dummy post data from the JSONPlaceholder API.
Transform:
Calculates the character length of the title and body fields.
Adds an etl_timestamp to every record.
Load: Saves the processed data into transformed_data.csv.
Logging: Records success or failure messages with timestamps in etl_log.txt.
Prerequisites
You will need Python 3 installed along with the following libraries:
pandas
requests
Installation
Install the required dependencies using pip:
Output Files
transformed_data.csv: The processed dataset containing original post data plus new length and timestamp columns.
etl_log.txt: A text file tracking each run of the script and any errors encountered.
