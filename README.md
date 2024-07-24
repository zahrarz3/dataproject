# dataproject
# Log File Analysis
## Introduction
This project involves the analysis of a log file to extract and analyze key fields such as IP address, timestamp, request method, URL, status code, response size, and query parameters. The objective is to gain insights from the log data and present the findings through visualizations.

## Data Extraction and Cleaning
The log file was parsed using Python with the help of regular expressions to extract the relevant fields. The extracted data includes:
- IP Address
- Timestamp
- Request Method
- URL
- Status Code
- Response Size (bytes)
- Query Parameters

The extracted data was then cleaned to handle missing values, format inconsistencies, and invalid entries.

## Data Analysis and Visualizations
The analysis was performed using Python and libraries such as Pandas and Seaborn. Key findings were visualized to provide insights into the log data.

### Visualizations
1. **Number of Requests per Method**
   ![Number of Requests per Method](path/to/request_method.png)

2. **Top 10 Requested URLs**
   ![Top 10 Requested URLs](path/to/top_urls.png)

3. **Status Code Distribution**
   ![Status Code Distribution](path/to/status_code_distribution.png)

4. **Response Size Distribution**
   ![Response Size Distribution](path/to/response_size_distribution.png)
