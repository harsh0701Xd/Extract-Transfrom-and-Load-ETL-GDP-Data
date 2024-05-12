# ETL Project: Extract, Transform, and Load GDP Data

## Introduction

In this practice project, we aim to create a complete ETL (Extract, Transform, Load) pipeline for accessing data from a website, processing it, and storing it in CSV format. The project scenario involves retrieving GDP data from a Wikipedia page and formatting it according to specific requirements.

### Project Overview

An international firm is expanding its business globally and requires an automated script to extract GDP data from a Wikipedia page maintained by the International Monetary Fund (IMF). The script must then transform this data into a consistent format and store it in CSV formats.

#### Project Tasks:

1. **Data Extraction:** Retrieve relevant information from the specified URL.
2. **Data Transformation:** Convert GDP information from million USD to billion USD and round to 2 decimal places.
3. **Data Loading:** Save the transformed data to CSV formats.

### Prerequisites

Ensure you have the following libraries installed:

- `pandas`
- `numpy`
