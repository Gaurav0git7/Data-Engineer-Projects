# Building-a-Spotify-Data-Pipeline: From-API-to-Power-BI-Insights


## Project Overview

This project demonstrates the creation of a data engineering pipeline using Spotify's real-time data and cloud-based ETL tools. The goal is to extract Spotify’s Top 50 Global Songs, process and clean the data, and visualize key insights using Power BI. The workflow integrates API interaction, ETL with AWS Glue, and data querying with Athena.

## Objectives

- Access Spotify’s Top 50 Global Songs data through its API using Python.
- Process and clean the extracted data to generate structured datasets.
- Use AWS Glue for data transformation and remove duplicates.
- Query the transformed data with AWS Athena.
- Visualize insights from the data using Power BI dashboards.

  

## Technologies Used

- **Spotify API:** For extracting real-time data.
- **Python:** For scripting data extraction using spotify API.
- **AWS S3:** For data storage.
- **AWS Glue:**  For data extraction, processing, and transformation with a codeless Visual ETL approach.
- **AWS Athena:** For querying the processed data stored in S3.
- **Power BI:** For visualizing insights and creating dashboards.


## Dataset Description

- **Albums.csv:** Contains information about Spotify albums.
- **Artists.csv:** Contains data about artists from Spotify’s top 50 tracks.
- **Songs.csv:** Contains data about artists from Spotify’s top 50 tracks.

## Project Setup

  ### Prerequisites
  - Spotify Developer account for API credentials.
  - AWS account with access to S3, Glue, and Athena.
  - Power BI desktop for visualization.

  ### Steps
   1. **Spotify API Access:**
      - Register an app on the Spotify Developer Portal.
      - Retrieve the Client ID and Client Secret for API access.
        
   2. **Data Extraction:**
      - Write a Python script to fetch the Top 50 Global Songs data using the Spotify API.
      - Save the extracted data into three CSV files: Albums.csv, Artists.csv, and Songs.csv.

   3. **Data Processing with AWS Glue-Visual etl:**

      - Upload the CSV files to an S3 bucket.
      - Use AWS Glue to create a visual etl job to process the data , removes duplicates and cleans the data.
      - Save the cleaned data back to S3.
     
   4. **Data Querying with AWS Athena:**

      - Use AWS Athena to analyze the cleaned data stored in S3.
      - Run SQL queries to check and refine the data.
    
   5. **Visualization in Power BI:**
      - Create Power BI dashboards to visualize the cleaned and queried data.
      - Extract meaningful insights through the visualizations.


## Future Enhancements
   1. Automate the pipeline using AWS Lambda.
   2. Include support for regional and genre-specific playlists.

## Contributing
  Contributions are welcome! If you have suggestions or improvements, please open a pull request or raise an issue.

## Contact Information
- **Gaurav Kumar**
- [LinkedIn](https://www.linkedin.com/in/gaurav-kumar-4724602a9/)

