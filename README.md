# Udacity Data Engineering Nanodegree - Project 3/6  
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat-square&logo=Python)](https://www.python.org/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square&logo=Microsoft-Academic)](https://lbesson.mit-license.org/)


## Data Warehouse
---  
  
## Introduction
A music streaming startup, Sparkify, has grown their user base and song database and want to move their processes and data onto the cloud. Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.
As their data engineer, I am tasked with building an ETL pipeline that extracts their data from S3, stages them in Redshift, and transforms data into a set of dimensional tables for the analytics team of Sparkify to continue finding insights in what songs their users are listening to.

## Project Description
In this project, i will apply what i've learned on data warehouses and AWS to build an ETL pipeline for a database hosted on Redshift. To complete the project, i will load data from S3 to staging tables on Redshift and execute SQL statements that create the analytics tables from these staging tables.


info:
distribution key all -> broadcasting on each cpu - small dimension tables, speed up joins
AWS Redshift copy json
https://docs.aws.amazon.com/de_de/redshift/latest/dg/copy-usage_notes-copy-from-json.html
AWS Redshift copy
https://forums.aws.amazon.com/thread.jspa?threadID=119125

Verlust der numerischen Präzision