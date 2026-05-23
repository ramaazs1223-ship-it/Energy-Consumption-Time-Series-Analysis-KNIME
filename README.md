Time Series Analysis: Energy Consumption Data Pipeline
Project Overview
This project focuses on the end-to-end data processing and visualization of historical energy consumption data. The goal is to transform raw, inconsistent data into structured time-series insights to identify consumption patterns, trends, and seasonality.
Technical Workflow (KNIME)
The workflow implemented in this project performs several critical data engineering tasks:
Data Ingestion: Accessing raw transaction and energy consumption datasets.
Data Transformation: Converting time values from String format to Date and Time objects for accurate temporal analysis.
Data Cleaning (Handling Gaps): Aligning the time series by applying Linear Interpolation to fill missing data points, ensuring a continuous and reliable dataset.
Aggregation: Calculating total energy values on Hourly, Daily, and Monthly scales.
Visual Analytics: Generating interactive Line Plots to visualize consumption totals and identify seasonal trends.
Key Features
Time Series Alignment: Sophisticated handling of data gaps.
Multi-Level Visualization: From granular hourly data to high-level monthly summaries.
Preprocessing Automation: A streamlined KNIME workflow that automates repetitive cleaning tasks.
Tools Used
KNIME Analytics Platform
Linear Interpolation Algorithms
Time Series Analysis Nodes
This project was completed as part of the Business Intelligence curriculum at the University of Petra
