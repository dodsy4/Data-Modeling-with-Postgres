# Overview
In this project I have created a SQL database for a music streaming service. The database is designed to inform buisness managers what music users are playing and when they are playing it. The data is originally stored in JSON logs along with the neccesary metadata. I have uploaded this data into a PostgreSQL database and have implemented an ETL pipeline for analysis.

# Schema Justification
In terms of the schema I have used a star schema which means that there is one fact table which contains the facts assocaited with each songplay and this table is accompanied by four dimensional tables  which each have a primary key that is referenced in the fact table.

# Justification of Relational Structure
With the dataset being small and the fact that we need to use joins as well as SQL, a relational database functions well in this use case. We also do not have much data to deal with which is anothe reason to use a relational database. 