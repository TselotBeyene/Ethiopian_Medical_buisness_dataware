# DataWare-Week6
This project is an advanced data warehousing solution designed to collect, store, and analyze data related to the medical industry in Ethiopia. The data is sourced from various platforms, including web scraping and Telegram channels. The system integrates robust ETL/ELT pipelines, advanced object detection techniques using YOLO, and data enrichment processes to generate actionable insights.

# Key Objectives
Centralized Data Storage: Gather and centralize data from diverse sources, including online platforms and social media channels.
Optimized Data Processing: Implement scalable ETL/ELT frameworks for handling both structured and unstructured data types.
Advanced Image Analysis: Integrate YOLOv5 for object detection and image-based data analysis.
Data Integrity and Quality: Use tools like DBT to ensure the data is accurate, clean, and reliable for further analysis.
# Project Structure
The repository is organized into the following directories to streamline development and management:

.github/workflows/: Contains GitHub Actions configuration files to enable continuous integration (CI), continuous deployment (CD), and automated testing workflows.

.vscode/: Configuration files for Visual Studio Code, optimizing the development environment for better workflow and coding efficiency.

Fast_API/: This folder includes the implementation of the machine learning model API, offering RESTful endpoints for seamless interaction with the model.

Kara_dbt/: Contains the DBT (Data Build Tool) project setup for transforming raw data into structured, insightful datasets, along with documentation to maintain data integrity.

database/: Includes scripts and configurations necessary for establishing and managing PostgreSQL database connections, facilitating smooth database interactions.

notebooks/: Contains Jupyter notebooks used for data exploration, feature engineering, initial modeling, and visualizing early-stage insights.

scripts/: Houses Python scripts for essential data preprocessing tasks, feature extraction, and the implementation of various data analysis models, such as credit scoring.

tests/: This folder is dedicated to unit tests to verify the accuracy and robustness of the data processing logic and machine learning models.

requirements.txt: Lists all the required dependencies and libraries necessary for the project setup, ensuring smooth installation and environment setup.

README.md: Provides comprehensive documentation for the project, including an overview, setup instructions, and detailed usage guidelines.