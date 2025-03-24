# Ride Sharing Data ETL and Analytics Pipeline

This project demonstrates a scalable data pipeline for a ride-sharing application using publicly available NYC taxi/ride data. The project covers the following aspects:

- **Data Extraction & Transformation:** Extract ride data from CSV files and transform it into a structured format using Pandas and PySpark.
- **Revenue Simulation:** Generate simulated revenue values for each ride.
- **Efficient Metadata Handling:** Demonstrate partition pruning, caching, and metadata management in PySpark.
- **Analytics Dashboard:** Build interactive dashboards with JupyterDash and Plotly to visualize ride trends and performance metrics.
- **Streaming & Rate Limiting (Production Context):** Provide example code for streaming ride data with Kafka and protecting API endpoints with a token bucket rate limiter.

## Features

- **ETL Pipeline:** Extracts, transforms, and loads ride data into a "ride fact" table.
- **Simulated Revenue:** Adds a simulated revenue column (between \$10 and \$25) for analysis.
- **Metadata Management:** Uses PySpark partitioning and caching to efficiently manage and query large datasets.
- **Interactive Dashboard:** Visualizes daily ride trends, rides by dispatching base, and more.
- **Streaming & API Rate Limiting:** Example code for integrating Apache Kafka and a token bucket algorithm using Flask.

## Project Structure

