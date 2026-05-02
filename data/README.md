# Data

This repository does not include raw patient data.

## Data Sources

All analyses were conducted using restricted-access critical care datasets available through PhysioNet:

- **MIMIC-IV** — Medical Information Mart for Intensive Care IV
  - Access: https://physionet.org/content/mimiciv/
  - Requires CITI Program certification and PhysioNet credentialed access

- **HiRID** — High Time Resolution ICU Dataset
  - Access: https://physionet.org/content/hirid/
  - Requires PhysioNet credentialed access

## Requesting Access

1. Complete the required CITI Program training in human subjects research
2. Create a PhysioNet account at https://physionet.org
3. Apply for credentialed access for each dataset
4. Once approved, data can be downloaded directly from PhysioNet

## Preprocessed Cohorts

Cohort selection scripts are provided in `src/cohort_selection.py`. These scripts
assume MIMIC-IV and HiRID data are available locally in the structure provided
by PhysioNet after download.

For questions about data access or preprocessing, contact: alexis@vitasignal.ai
