# Airflow

Business Context
Following the epidemic, it became imperative to keep track of medical health on a regular basis. The cost of this diagnosis, on the other hand, has increased. Dx-diagnostics, an online medical health tracker startup, plans to create an application to enable users to measure their health indicators at regular intervals. It also hopes to gain a big foothold in the pharmaceutical industry by reaching as many patients as possible.
Problem Statement
This program is still in the prototype stage, and it will take a lot of experimentation and iterations to come up with a simple workflow that can automate a patient's health tracking system. But as a minimum viable product, the CEO of the firm expects a basic service to be accessible soon, allowing him to analyze the market's demand for it and make the necessary decisions to improve or alter the services provided.
Objective
As an analytics engineer, you'll be in charge of designing an Airflow DAG in the cloud to serve as the prototype's backend data architecture. The DAG should calculate the summary statistics of the heart rate and O2 levels of the patient every 15 mins and send it as a report over a Slack channel. The anomalies in these metrics also need to be flagged and saved separately. You've been granted access to a patient's data for this objective, and if it works, it can be scaled out to include other patients.
Data Description
The data has a patient's health indicators over a certain period of interval in a day. The detailed data dictionary is given below.
•	patient_id: UNIQUE ID of a patient
•	timestamp: Time at which a metric was recorded
•	o2_level: Indicates the O2 level of the patient measured in percentage of oxygen saturation
•	heart_rate: Indicates the Heart Rate of the patient measured in beats per minute
