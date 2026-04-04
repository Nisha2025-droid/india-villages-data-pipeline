# India Villages Data Pipeline 🇮🇳

## Project Overview
A data cleaning and processing pipeline built for the 
All India Villages API platform. This project processes 
raw MDDS government data of 600,000+ villages across 
India into a clean, structured format ready for 
database import.

## Problem Statement
The raw data was provided as 30 separate state-wise 
Excel files with inconsistent formatting, duplicate 
records, and missing values. The goal was to clean 
and merge all files into one structured dataset.

## What I Did
- Explored 30 state-wise Excel files
- Identified and resolved data quality issues
- Removed 238 duplicate village codes
- Removed summary rows and null values
- Stripped extra whitespace from all text fields
- Merged all states into one clean CSV

## Key Results
| Metric | Value |
|--------|-------|
| Total Villages | 5,64,159 |
| Total States | 29 |
| Total Districts | 524 |
| Total SubDistricts | 5,093 |
| Duplicates Removed | 238 |
| Null Values Fixed | 1 |
| File Size | 32.6 MB |

## Tools Used
- Python
- Pandas
- Jupyter Notebook
- VS Code

## Data Source
MDDS — Ministry of Drinking Water and Sanitation, 
Government of India

## Project Structure
DataCleaning.ipynb — Main data cleaning notebook
README.md — Project documentation

## Key Challenges
- Uttar Pradesh file was in .ods format 
  (different from other states)
- Madhya Pradesh file was corrupted/incomplete 
  from source
- 238 duplicate village codes across different states
