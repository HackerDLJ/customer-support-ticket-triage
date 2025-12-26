# customer-support-ticket-triage
Week-1 Internship Project

# Project Description:
## Customer Support Ticket Analysis

This project involved a comprehensive analysis of customer support ticket data to extract key insights, classify issues, assign priority levels, and evaluate Service Level Agreement (SLA) performance. The main objectives were:

Data Loading and Exploration: Loading the raw customer support ticket data and performing initial exploration to understand its structure, dimensions, and identify missing values.

Rule-Based Issue Classification: Implementing a rule-based system to classify tickets into predefined categories (e.g., PAYMENT, LOGIN, DELIVERY, REFUND, BUG, TECHNICAL, GENERAL) based on keywords in ticket subjects and descriptions.

Rule-Based Priority Assignment: Assigning priority levels (P0 to P3) to tickets using a similar rule-based approach, distinguishing between critical, major, minor, and general issues.

SLA Calculation: Calculating the SLA hours and determining the SLA due time for each ticket based on its assigned priority and purchase date.

Key Metrics Analysis: Analyzing overall ticket statistics, distributions of classified issues and assigned priorities, and SLA performance metrics, including the number and percentage of breached SLAs.

Data Visualization: Generating various plots, such as bar charts for issue and priority distributions, and line plots for SLA due date distributions, to visually represent key findings.

Managerial Reporting: Compiling a textual summary report for support managers, detailing insights into ticket volume, prevalent issue types, priority distribution, and SLA adherence.

Data Export: Exporting the enhanced dataset, including the new 'Classified Issue', 'Assigned Priority', 'SLA Hours', and 'SLA Due Time' columns, into a new CSV file for further use.

Version Control Integration: Managing the project files (notebook and output CSV) using Git and GitHub for version control and sharing.

- *Made By, DLJ (*LUKE JEBASUNDAR*)*

## Tools Used:

Python: The primary programming language used for all data processing and analysis.

Pandas: A powerful Python library used extensively for data manipulation, cleaning, reading/writing CSVs, date/time operations, and statistical aggregations.

Matplotlib: A Python plotting library used for creating static, interactive, and animated visualizations.

Seaborn: A Python data visualization library based on matplotlib, providing a high-level interface for drawing attractive and informative statistical graphics.

Git: A distributed version control system used for tracking changes in source code during software development, and for coordinating work among developers.

GitHub: A web-based platform for version control and collaboration, hosting the project's Git repositories.

Google Colab: The cloud-based Jupyter notebook environment used for developing and running the code.

shutil module: Python's high-level file operations module for copying files.

os module: Python's module for interacting with the operating system, used for path manipulations.

getpass module: Python's module for secure password entry, used for GitHub PAT input.

