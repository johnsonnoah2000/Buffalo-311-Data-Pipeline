# Buffalo-311-Data-Pipeline

A full end-to-end data pipeline built in Python using real City of 
Buffalo open data.

## What it does
- Ingests raw 311 service request data from data.buffalony.gov
- Cleans and standardizes messy real-world data using pandas
- Engineers new features like response time and seasonal patterns
- Classifies every complaint by priority using rule-based logic
- Trains a Random Forest ML model to predict priority automatically
- Uses Claude AI as a conversational analyst to answer questions
  about the fully processed dataset

## Tech Stack
Python · pandas · scikit-learn · Anthropic Claude API · Google Colab

## Data Source
City of Buffalo Open Data Portal — 311 Service Requests
data.buffalony.gov
