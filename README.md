Overview:

UberData Insights is a comprehensive project aimed at leveraging modern data engineering techniques and Google Cloud Platform (GCP) services to extract, transform, and analyze Uber ride data. By harnessing the power of Mage Pipeline, BigQuery, and Jupyter notebooks, this project seeks to provide valuable insights into Uber's operations.

Project Components:

Mage Pipeline Files: Contains scripts and configurations for the Extract, Transform, Load (ETL) process using Mage Pipeline. These files enable the cleaning, transformation, and loading of Uber ride data into Google BigQuery.

Data: The 'data' directory includes the raw Uber ride dataset (uber_data.csv), which serves as the primary data source for analysis and transformation.

Jupyter Notebook for Transformation: The 'Jupyter' directory houses Jupyter notebook files containing code for ETL transformation of the Uber ride data. These notebooks provide an interactive environment for exploring and processing the data before analysis.

Analytics Query: The 'analytics_query.sql' file contains SQL queries for performing analytics on the transformed data in Google BigQuery. These queries enable various analytical tasks, including aggregations, filtering, and deriving actionable insights.

Architecture Diagram: The 'architecture.jpg' file depicts the architecture of the UberData Insights project, illustrating the flow of data from extraction to analysis using Mage Pipeline, BigQuery, and Jupyter notebooks.

Data Model: The 'data model.png' file showcases the dimensional modeling of tables used in the project. This model defines relationships and attributes to facilitate efficient data storage and retrieval for analysis purposes.

Commands: The 'commands.txt' file contains a list of Ubuntu and Google Virtual Instance commands for setup and execution of the project. These commands provide guidance on configuring the environment and running the project components seamlessly.

Usage:

Begin by setting up the project environment and configuring Mage Pipeline, Google Cloud Platform services, and dependencies.
Execute the Mage Pipeline scripts to extract, transform, and load the Uber ride data into Google BigQuery.
Explore the Jupyter notebooks to further transform and analyze the data, generating visualizations and insights.
Utilize the provided SQL queries in the 'analytics_query.sql' file to perform advanced analytics on the transformed data in BigQuery.
Refer to the architecture diagram and data model for a comprehensive understanding of the project's structure and data flow.
Follow the instructions in the 'commands.txt' file for executing various commands related to setup and execution of the project components.
