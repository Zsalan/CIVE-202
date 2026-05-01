# CIVE-202 Project 1

Project-1
Air Quality Analysis Using AirPurple Sensor Data

This Python Programming Assignment 1 is completed by Abdi Aden for CIVE 202 and is intended to be shared with the instructor.

---

## Purpose

This project involves the analysis of real-world air quality data collected across Nebraska. The dataset comes from AirPurple sensors and includes environmental and pollutant measurements.

The project involves the following:

AirPurple Sensor Data – statewide air quality monitoring data

The purpose of the project is:
To organize and clean raw environmental data
To calculate summary statistics for air pollutants (VOC, PM2.5, PM10)
To identify locations with the highest pollution levels
To detect maximum pollution events (date and location)
To analyze how temperature, humidity, and elevation affect air quality
To identify unhealthy air quality conditions based on thresholds
To demonstrate the use of Python in engineering data analysis

The project also shows the potential for Python to be used as an engineering tool instead of traditional tools such as Excel. 

---

## Repository Contents

This repository includes all the required materials for Project #1. The materials are as follows:

README.md

A summary of the project and a guide on how to run the code

Scope of Work (SOW)

A detailed outline of the project activities and requirements

Annotated Code Document (ACD)

An explanation of the Python code written

Technical Report

A comprehensive report including introduction, methods, results, and discussion

Python Code (.ipynb)

A Jupyter Notebook used to perform the analysis

Dataset (CSV)

Air quality data collected from AirPurple sensors

---

## How to Run the Code

Make sure you have Python installed with the following libraries:

```bash
pip install pandas numpy
```

Open the file:

```
Project1AbdiAden.ipynb
```

in Jupyter Notebook or VS Code

Run each section top to bottom:

---

### Import Libraries

Loads pandas and numpy for data processing

---

### Load Dataset

Reads the AirPurple CSV dataset into a DataFrame

---

### Data Cleaning

Ensures correct formatting
Removes or handles missing values
Prepares variables for analysis

---

### Data Processing

Groups data by sensor location

Calculates summary statistics:
Mean
Median
Max
Min

Identifies top 5 polluted sensors

Finds maximum pollution events:
VOC
PM2.5
PM10

Filters unhealthy VOC events (VOC ≥ 25)

Creates environmental categories:

Temperature Levels:
Below Freezing
Cool
Warm
Hot

Altitude Levels:
Low
Medium
High

---

### Data Analysis

Evaluates how temperature and altitude affect VOC levels

Groups and compares pollutant levels under different conditions

Creates pivot tables for summarized results

---

### Data Output

After running the code the program will:

Display top polluted sensors
Show maximum pollution events
List unhealthy VOC readings
Provide summary tables of air quality statistics

---

## Results

Pollution levels vary across different sensor locations
Certain sensors consistently show higher pollutant levels
VOC levels tend to increase in warmer temperatures
Maximum pollution events occur at specific dates and locations
Some readings reach unhealthy levels for sensitive groups
Environmental conditions influence pollutant behavior 

---

## Engineering Relevance

This project is important for:

Environmental monitoring
Public health analysis
Air quality assessment
Data-driven decision making
Infrastructure and urban planning

---

## Project Timeline

The project followed a structured schedule including:

Data collection and review
Data cleaning and preparation
Statistical analysis
Environmental factor analysis
Report writing

(Look at Scope of Work for full breakdown) 

---

## Work Summary

Total Hours Worked: (add your actual time)

Tasks included:

Data cleaning
Data analysis
Code development
Debugging
Report writing

---

## Final Deliverables

Python Code (.ipynb)

Annotated Code Document

Scope of Work

Technical Report

Dataset (CSV)

GitHub Repository

---

## References

AirPurple Sensor Data Documentation
EPA Air Quality Index (AQI)
AirNow Air Quality Data
UNMC Water, Climate and Health Group
CIVE 202 Course Materials

---
