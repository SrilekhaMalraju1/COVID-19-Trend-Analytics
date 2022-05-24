# COVID-19-Trend-Analytics

INTRODUCTION:
PROJECT REPORT
 For Big Data Hands-On project, I have implemented a pipeline which consists of extract/ download, transform, and visualize. I have applied knowledge and skills learned in this course work and enhanced learning from online content available and implemented in this project. The environment I will be using in the project is Google Cloud Platform. Additionality I will be using Data Cleaning / quality assurance techniques and pipelines in this project. The motive of this project is to utilize the tools and concepts learnt from the course work, hence I will be developing a pipeline where I thought of choosing the dataset by downloading manually from the source and uploading in GCP cloud storage bucket, but as this process is manual, to automate the pipeline refresh process I will select the public datasets available in GCP marketplace. I will then perform transformations on the data and create the required insights and store in a BigQuery table. I will schedule the query with relevant frequency, so that dataset refresh and transformation steps will be automated. Next step is to analyze and create visualizations with the transformed dataset using Power BI tool. I will create connection in Power BI with BigQuery dataset and establish the live connection. this way visuals will be automatically refreshed when the Power BI refresh is done. Overall goal is to implement an automated pipeline with maximizing the use of tools and concepts learnt in INFO-I535 course.
 
 
BACKGROUND:
The problem statement was selected to implement the pipeline using Google Cloud Platform. This problem statement addresses use of multiple concepts present in the course modules, like Data types, data world, Data pipeline and lifecycle, GCP, Qwiklabs sessions related to Google cloud, data visualization, Ingestion and storage, Data modelling. I have selected this project because GCP is great platform to ingest data, store in cloud, transform using BigQuery. Any complex dataset can be worked on in GCP, with automated query refreshes and establish connections with external visualization tools. This project outcome will be an ETL automated pipeline with learning outcomes like working with GCP, BigQuery and Power BI.
The dataset I have selected for this project is COVID – 19 cases in the world which is a public dataset created by Johns Hopkins University. This data is updated every day and is at date level. I want to aggregate the data to month level as viewing the data and reports at day level will be very complex and not insightful. I want to create insights of the datapoints like Cases confirmed and deaths across the country, state and month and year level. Converting the dataset from day level to month level makes the problem statement interesting and important, and using GCP and BigQuery to obtain the results.
