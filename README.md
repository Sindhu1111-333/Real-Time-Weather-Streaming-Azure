# Real-Time Weather Data Streaming and Alert System using Azure

## Overview
This project implements a real-time weather data streaming system using Azure services. It continuously fetches weather and air quality metrics (such as temperature, humidity, and air quality index) from external APIs, processes the data, and loads it into a PostgreSQL database.

The system streams and processes weather data in real-time, ensuring that the latest updates are available for analysis and visualization. Additionally, it includes an automated alert mechanism that sends email notifications when extreme weather conditions are detected.

#Data source
http://api.weatherapi.com


## Key Features
- Real-time data ingestion using Azure Databricks and Azure Functions.
- Real-time dashboard in Power BI for weather visualization.
- Email alerts for extreme weather conditions using Data Activator.

## Technologies Used
- Programming Language: Python
- Azure Databricks – For data processing and transformation.
- Azure Functions – To trigger and manage data ingestion.
- Event Hub – For streaming real-time weather data.
- Microsoft Fabric – For data integration and analytics.
- Kusto DB – To store and query weather data efficiently.
- Power BI – For real-time weather visualization and reporting.
- Data Activator – To set up automated alerts for extreme conditions.
- Azure Key Vault – For secure storage of API keys and credentials.

## Setup Instructions
1. Clone the repository.
2. Set up Azure resources: Deploy Azure Databricks, Event Hub, and Microsoft Fabric.
3.Configure Azure Functions and Databricks: Set up data ingestion workflows.
4.Deploy Power BI dashboard and Data Activator alerts: Connect your data sources for visualization and notifications

## Usage
- Access the Power BI dashboard for real-time weather updates.
- Configure alerts in Data Activator to receive notifications for extreme weather conditions.
 



