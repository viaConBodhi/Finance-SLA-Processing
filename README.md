![My Project Logo](https://github.com/viaConBodhi/Finance-SLA-Processing/blob/main/images/logo.png)

# Finance-SLA-Processing

## Overview
Finance-SLA-Processing is an automated solution for processing service agreements through API integration of Jira, Docusign, and Smartsheets. This project streamlines the workflow for service level agreement (SLA) processing, ensuring accuracy, efficiency, and compliance with financial and service standards.

## Features
- Automated processing of SLA-related tasks and invoicing.
- Integration with Jira, Docusign, and Smartsheets for seamless workflow.
- Data extraction and parsing from Jira tickets to identify SLA requirements.
- Automated generation and processing of invoices through Docusign.
- Tracking and updating of SLA progress in Smartsheets.

## Requirements
- Python 3.9+
- smartsheet-python-sdk 2.105.0
- PyPDF2
- pandas
- re (Regular Expression module)
- requests
- pyodbc
- sqlalchemy

## Installation
To set up the project environment, install the required Python packages using pip:

```bash
pip install smartsheet-python-sdk==2.105.0 PyPDF2 pandas requests pyodbc sqlalchemy
```
## Usage
The project is structured as a Jupyter Notebook (SLA-create.ipynb) containing the complete workflow for processing SLAs. Follow the steps in the notebook to configure your API keys and database connections.

## Key Steps:
- Load Jira tables to identify SLAs pending processing.
- Extract and parse relevant data from Jira tickets for SLA requirements.
- Update and manage SLA records in Smartsheets.
- Generate and process SLAs automatically through Docusign integration.

# Configuration
Before running the notebook, ensure you have set up the necessary API keys and database connections:

- api_key: Your Smartsheet API key.
- sheet_id: The ID of your Smartsheet.
- Database connection settings for accessing Jira records.

## Contribution
Contributions to the Finance-SLA-Processing project are welcome. Please ensure to follow best practices for code contributions and pull requests.

License
This project is licensed under the GPL-3.0 License - see the LICENSE file for details.
