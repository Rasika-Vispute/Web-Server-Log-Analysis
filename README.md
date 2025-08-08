# Web-Server-Log-Analysis
This project focuses on analyzing ~726,000 raw HTTP server log entries from the **University of Calgary** to uncover insights related to user behavior, website traffic patterns, error occurrences, and bandwidth usage. The goal was to work with real-world web server log data to extract meaningful insights and demonstrate your Python data analysis skills that transforms unstructured logs into structured datasets for analysis, visualization

## Project Objectives
- Parse raw web server logs into structured formats.
- Analyze traffic trends, request types, and status codes.
- Identify behavioral patterns and anomalies in user access.
- Prepare the dataset for potential anomaly detection
  
## Part 1: Data Loading and Cleaning
**1. Download and Load Data** 
- Download the compressed dataset from the FTP server 
- Handle the `.gz` compression format appropriately 
- Load the data into a suitable Python data structure 
- Implement proper error handling for network/file operations 

**2. Data Cleaning**
- Parse timestamp strings into `datetime` objects                                                                                         
- Extract file extensions from the filename field 
- Handle missing or malformed data entries 
- Convert data types appropriately (integers, strings, etc.) 
- Remove or flag invalid log entries

## Part 2: Key Questions Explored
Q1: Count of total log records

Q2: Count of unique hosts

Q3: Date-wise unique filename counts

Q4: Number of 404 response codes

Q5: Top 15 filenames with 404 responses

Q6: Top 15 file extension with 404 responses

Q7: Total bandwidth transferred per day for the month of July 1995

Q8: Hourly request distribution

Q9: Top 10 most requested filenames

Q10: HTTP response code distribution

##  What I Did
- **Log Parsing:** Extracted meaningful fields (IP, datetime, method, URL, status code, bytes sent) from raw Apache-style logs using **Python** and **Regex**.
- **Data Cleaning & Structuring:** Converted logs into a clean, tabular format using **Pandas**.
- **Exploratory Data Analysis (EDA):** Visualized request frequency, traffic trends, top resources, and error distribution using **Matplotlib** and **Seaborn**.
- **Feature Engineering:** Created new features like request hour, day of week, response category, and grouped IP behaviors.

##  Tools & Technologies Used
`Python` · `Pandas` · `Regex` · `Matplotlib` · `Seaborn` · `Scikit-learn`  
`Data Cleaning` · `Log Parsing` · `Time-Series Analysis` 

##  Contributions
Suggestions, improvements, and issues are welcome. Feel free to fork the repo or raise a pull request!

## Contact
**Rasika Vispute**  
Email: rasikavispute32@gmail.com 
LinkedIn: https://www.linkedin.com/in/rasikavispute/



