# Tokyo_Olympics_Azure_Data_Engineering_Project
* Orchestrated data extraction and ingestion using Azure Data Factory from public APIs, successfully handling datasets related to 11,000 athletes across 47 disciplines. 
* Implemented data transformations and cleaning using Apache Spark within Azure Databricks, enhancing data quality by removing duplicates and null values.  
* Utilized Azure Data Lake Storage Gen2 for efficient data storage management, ensuring seamless data flow between raw and transformed datasets.  
* Conducted advanced data analytics with Azure Synapse Analytics, generating actionable insights from transformed data, such as medal counts and participant statistics.   
* Managed the entire lifecycle of a cloud-based data pipeline on Azure, from setup and configuration to data processing and visualization, demonstrating strong project management and technical skills.  


## Project Architecture

This project demonstrates a comprehensive data engineering pipeline using various Azure services along with popular data visualization tools. Below is a simple flowchart of the project's architecture:

- **Data Source** ---> Initial point where raw data originates.
- **Data Factory** ---> Ingests data from the data source for preliminary processing.
- **Raw Data Store (Data Lake Gen 2)** ---> Stores the raw data for further processing and transformation.
- **Azure Databricks** ---> Performs data transformation to prepare the data for analysis.
- **Transformed Data Store (Data Lake Gen 2)** ---> Holds the transformed data ready for analytical processing.
- **Azure Synapse Analytics** ---> Processes transformed data to extract actionable insights.
- **Power BI and Looker Studio** ---> Visualization tools used to create dashboards for data reporting.


**Step-by-step breakdown follows the logical flow from data ingestion to visualization, demonstrating a comprehensive approach to building a scalable and robust Azure data engineering solution.**  

1. **Data Source Integration:**
   - Setting up Azure Data Factory to connect to various data sources where the Olympic data was stored.
   - Configured data ingestion pipelines within Azure Data Factory to automate the extraction of data, ensuring that data from APIs and other sources was reliably ingested into Azure Data Lake Storage Gen 2.

2. **Raw Data Storage:**
   - Utilized Azure Data Lake Storage Gen 2 to store the ingested raw data. This setup allowed for scalable, big data storage solutions that supported both structured and unstructured data.
   
3. **Data Transformation:**
   - Leveraged Azure Databricks to perform data transformations. Apache Spark in Databricks was used to clean, process, and transform the raw data into a more analytics-friendly format.
   - Tasks like removing duplicates, handling data types, and structuring the data were completed to prepare the data for detailed analysis.

4. **Transformed Data Management:**
   - The transformed data was then stored back into Azure Data Lake Storage Gen 2, but in a separate container or folder designated for transformed data, keeping it organized and accessible for analytics.

5. **Analytics:**
   - Azure Synapse Analytics was used to run complex SQL queries on the transformed data to derive insights and generate analytical results.
   - This step involved deep analysis to understand patterns such as medal counts by country, athlete performance metrics, and other key statistics.

6. **Visualization:**
   - Developed interactive dashboards using Power BI, and also utilized tools like Looker Studio and Tableau for robust data visualization.
   - These dashboards provided real-time insights through visual representations, making the data easy to understand and actionable for decision-makers.


## Technology Used

- Microsoft Azure  
      Data Factory  
      Data Lake Storage Gen2  
      Databricks  
      Synapse Analytics   
- Visualization:   
      Power BI  
      Looker Studio   

