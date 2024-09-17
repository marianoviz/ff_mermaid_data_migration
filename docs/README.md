# FF Data Migration to MERMAID

## Project Overview

This project aims to migrate historical data from the Fish Forever (FF) program to the online platform MERMAID. The repository contains the necessary scripts, data, and documentation to accomplish this task.


## Repository Structure

ff_mermaid_data_migration/
├── data/
│   ├── raw/
│   ├── preprocessed/
│   ├── processed/
│   ├── metadata/
├── src/
│   ├── data_processing/
│   │   ├── honduras/
│   │   │   ├── coralnet/
│   │   │   ├── ff2.0/
│   │   ├── mozambique/
│   │   │   ├── ff2.0/
│   │   ├── indonesia/
│   │   │   ├── ff2.0/
│   │   │   ├── op41/
│   │   ├── philippines/
│   │   │   ├── ff2.0/
│   │   │   ├── op41/
│   ├── data_migration/
│   │   ├── honduras/
│   │   │   ├── coralnet/
│   │   │   ├── ff2.0/
│   │   ├── mozambique/
│   │   │   ├── ff2.0/
│   │   ├── indonesia/
│   │   │   ├── ff2.0/
│   │   │   ├── op41/
│   │   ├── philippines/
│   │   │   ├── ff2.0/
│   │   │   ├── op41/
├── docs/
│   ├── README.md
│   ├── data_dictionary.md
│   ├── setup_instructions.md
├── tests/
│   ├── test_data_integrity.R
│   ├── test_data_upload.R
├── ff_mermaid_data_migration.Rproj


## Folder Descriptions

- **data/**: Contains all data files.
  - **raw/**: Original, unprocessed historical FF data.
  - **preprocessed/**: Datasets that have undergone initial processing for sharing purposes but are not yet ready for ingestion into MERMAID.
  - **processed/**: Cleaned and finalized datasets ready for upload to MERMAID.
  - **metadata/**: Metadata files describing the structure and content of the data.

- **src/**: Contains all R scripts for data processing and migration.
  - **data_processing/**: Scripts and folders for processing data from various regions.
    - **honduras**, **mozambique**, **indonesia**, **philippines**: Regional folders containing specific processing scripts.
    - **coralnet/**, **ff2.0/**, **op41/**: Subfolders within each region for organizing scripts based on data sources or survey types.
  - **data_migration/**: Scripts for preparing data from various regions for upload to MERMAID, organized similarly to the **data_processing** folder structure.

- **docs/**: Project documentation.
  - **README.md**: Overview of the project.
  - **data_dictionary.md**: Detailed description of the data fields and their meanings.
  - **setup_instructions.md**: Instructions for setting up the project environment.

- **tests/**: Scripts for testing data integrity and upload processes.
  - **test_data_integrity.R**: Script to ensure data is clean and consistent before upload.
  - **test_data_upload.R**: Script to verify the data upload process to MERMAID.

- **ff_mermaid_data_migration.Rproj**: R project file for managing the workspace.