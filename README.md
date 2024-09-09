**Financing the 2030 Agenda for Sustainable Development - Data Analytics Project**

This repository contains the code and resources for the data analytics engineering project focusing on the "Financing the 2030 Agenda for Sustainable Development" dataset. This project involves downloading, cleaning, transforming, and analyzing data related to the United Nations Sustainable Development Goals (SDGs), with an emphasis on financing aspects of global development.

Table of Contents
•	Project Overview
•	Dataset
•	Requirements
•	Setup and Installation
•	Usage
•	Features
•	Contributing

Project Overview:
The primary objective of this project is to automate the processing of large-scale datasets related to financing the 2030 Agenda for Sustainable Development. We utilize Python and OpenRefine to clean and transform data, ensuring that large numeric values are formatted for easy readability and analysis. The end goal is to produce insights that can contribute to understanding global financing trends related to the SDGs.

Objectives:
1.	Automate data extraction and formatting processes.
2.	Clean and transform numeric values into a standard dollar format with commas.
3.	Perform exploratory data analysis (EDA) and basic statistical analysis.
4.	Provide insights into financing trends for sustainable development.
   
Dataset:
The dataset used in this project is publicly available and can be accessed from the AidData portal:
•	Dataset URL: Financing the 2030 Agenda for Sustainable Development - Version 1.0
Once downloaded, the dataset will be automatically extracted and processed using the provided scripts.

Requirements:
To run this project, you'll need to install the following dependencies:
•	Python 3.x
•	Pandas
•	Requests
•	Zipfile (Standard Python Library)
•	Jupyter Notebook (Optional, for interactive data exploration)

Setup and Installation:
•	Clone the Repository:
  git clone [https://github.com/your-username/financing-2030-agenda.git](https://github.com/Prabhukiranpk26/United-National-Sustainable-Development-Goals.git)
  cd financing-2030-agenda
•	Download the Dataset: The script automatically downloads the dataset from the provided URL. Ensure you have a stable internet connection.
•	Run the Data Processing Script: Execute the script that downloads, extracts, and processes the dataset: python data_processing.py
•	Explore the Data: You can explore the dataset interactively using Jupyter Notebook: jupyter notebook financing_2030_agenda_analysis.ipynb

Usage:
Data Cleaning: The data_processing.py script handles data cleaning, including extracting and formatting numeric values in dollar format.
Data Exploration: The financing_2030_agenda_analysis.ipynb notebook provides an interactive way to explore the data, perform statistical analysis, and visualize trends.
Analysis: You can extend the analysis by adding your own custom code for more in-depth exploration of financing trends related to the SDGs.

Notebooks:
•	financing_2030_agenda_analysis.ipynb: Interactive notebook that walks through data loading, cleaning, exploration, and visualization.
Scripts:
•	data_processing.py: Python script to download, extract, and clean the dataset.
Features
•	Automated Data Processing: Script to download and extract data automatically.
•	Data Cleaning: Transform large numeric strings into dollar format with commas.
•	Exploratory Data Analysis (EDA): Perform basic EDA to gain insights into financing trends.
•	Jupyter Notebook Integration: Interactive notebooks to visualize and analyze the data.

Contributing: 
Contributions are welcome! If you find a bug, have an idea for an improvement, or want to add new features, please open an issue or submit a pull request.
•	Fork the repository.
•	Create your feature branch (git checkout -b feature/your-feature-name).
•	Commit your changes (git commit -m 'Add your feature').
•	Push to the branch (git push origin feature/your-feature-name).
•	Open a pull request.




