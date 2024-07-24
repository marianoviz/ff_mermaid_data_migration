# FF Data Migration to MERMAID

## Project Overview
This project aims to migrate historical data from the Fish Forever (FF) program to the online platform MERMAID. The repository contains the necessary scripts, data, and documentation to accomplish this task.

## Repository Structure

ff_data_migration_to_mermaid/
├── data/
│ ├── raw/
│ ├── processed/
│ ├── metadata/
├── src/
│ ├── data_processing/
│ ├── data_migration/
├── docs/
│ ├── README.md
│ ├── data_dictionary.md
│ ├── setup_instructions.md
├── tests/
│ ├── test_data_integrity.R
│ ├── test_data_upload.R
├── .gitignore
├── LICENSE
├── requirements.txt
└── main.R

## Folder Descriptions

- **data/**: Contains all data files.
  - **raw/**: Original historical FF data.
  - **processed/**: Processed or cleaned data ready for upload to MERMAID.
  - **metadata/**: Metadata files describing the data.

- **src/**: Contains R scripts.
  - **data_processing/**: Scripts for cleaning and preparing the data.
  - **data_migration/**: Scripts for uploading the data to MERMAID.

- **docs/**: Project documentation.
  - **README.md**: Overview of the project.
  - **data_dictionary.md**: Description of the data fields and their meanings.
  - **setup_instructions.md**: Instructions for setting up the project.

- **tests/**: Scripts for testing data integrity and upload processes.
  - **test_data_integrity.R**: Ensures data is clean and consistent.
  - **test_data_upload.R**: Verifies the upload process to MERMAID.

- **.gitignore**: Specifies files and directories to be ignored by Git.
- **LICENSE**: License for the repository.
- **requirements.txt**: List of R packages and dependencies required for the project.
- **main.R**: Main R script orchestrating the data migration process.
