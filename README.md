# Hospital Admission Records Analysis

## Team Members
* Afnan Tayem

## Project Overview

This project analyzes hospital admission records to identify trends in patient admissions, such as common diagnoses, seasonal patterns, and demographic distributions. The goal is to help healthcare teams better understand patient flow and support data-driven decisions. The final output will include visualizations and summary insights generated using Python.

## Data Sources

The project relies on hospital admission logs, with details such as the date of admission, patient demographics, diagnosis group, and duration of stay.
The data is not tracked in this repository. Instructions for how to get and place the data files before running any analysis are provided in the set up below.
Expected data location example: data/raw/admissions.csv

## Project Structure

The repository is organized as follows:

* `README.md` — project documentation
* `requirements.txt` — Python dependencies
* `setup.sh` — script to prepare the project environment
* `test_environment.py` — environment validation script
* `AGENTS.md` — guidelines for AI-assisted contributions

Future directories may include:

* `data/` — raw and processed datasets
* `notebooks/` — exploratory data analysis
* `src/` — project scripts and data processing code

## Setup Instructions

1. Clone the repository.
2. Run the setup script to create the environment and install dependencies:

./setup.sh

On Windows, the script may not run directly in CMD or PowerShell. Use Git Bash or run the commands manually.

3. After setup, verify the environment:

python test_environment.py

## Usage

After setting up the environment and placing the dataset in the `data/raw/` directory, run the analysis scripts or notebooks to explore the hospital admission data and generate insights.

## Contributing

Before committing any changes, ensure that the environment test passes:

python test_environment.py

All contributors should review AI-generated code and verify that it runs correctly before pushing changes to the repository.
