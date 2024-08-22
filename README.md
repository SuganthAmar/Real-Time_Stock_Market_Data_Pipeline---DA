# Real-Time Stock Market Data Pipeline

![Project Screenshot](https://github.com/SuganthAmar/Real-Time_Stock_Market_Data_Pipeline---DA/blob/main/asset/Screenshot%202024-08-22%20211440.png)

## Overview

This project simulates real-time data streaming from CSV files and transmits it to Apache Kafka via a producer, enabling a dynamic data flow for processing. The Kafka consumer retrieves and processes the data, with AWS automatically pushing the formatted data to S3 for efficient storage and access.

## Key Features

- **Real-Time Data Simulation:** Data from CSV files is streamed in real-time to Apache Kafka, ensuring continuous and dynamic data flow.
- **Data Processing:** Configured a Kafka consumer to process the streaming data effectively.
- **AWS Integration:** 
  - **AWS S3:** Automatically stores and formats data for efficient retrieval.
  - **AWS Glue Crawler:** Creates a DataCatalog to organize and manage data.
  - **AWS Athena:** Allows seamless querying and analysis of the stored data.

## Tech Stack

- **Python**
- **Apache Kafka**
- **AWS S3**
- **AWS Glue**
- **AWS Athena**

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SuganthAmar/Real-Time_Stock_Market_Data_Pipeline---DA.git
2. **Set up Apache Kafka:**

Follow the Kafka documentation to install and configure Kafka.
3. **Simulate Real-Time Data:**

- Run the Python script to start streaming data from the CSV files.

4. **Process Data with Kafka:**

- Configure and start the Kafka consumer to begin processing the data.

5. **Store Data on AWS:**

- AWS will automatically push the formatted data to S3. Ensure AWS credentials are properly configured.

6. **Query Data with AWS Athena:**

- Use AWS Glue Crawler to create a DataCatalog, and then query the data using AWS Athena.
