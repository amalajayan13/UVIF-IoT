# UVIF-IoT: Uncertainty-aware, Validated, Interpretable, and Feature-efficient IoT intrusion detection

## Reproducibility
The full experiment is implemented in `main.ipynb` and can be executed locally or in Google Colab. The notebook performs dataset audit, preprocessing, model training, calibration, robustness evaluation, edge-efficiency analysis, and forensic triage export.

## Dataset
This project uses the N-BaIoT dataset:

Yair Meidan (2025). **N-BaIoT**. IEEE Dataport.  
DOI: https://dx.doi.org/10.21227/y9de-qj71  
Link: https://ieee-dataport.org/documents/n-baiot

The dataset is not redistributed in this repository. Users should download it from IEEE Dataport and place it in the project directory or update the dataset path in the notebook.

## Outputs
Generated outputs are saved under `outputs/`, including CSV/LaTeX tables, PDF/PNG figures, trained model artifacts, logs, and cyberforensics-supportive triage files such as event ledgers, uncertainty-ranked events, false positives, false negatives, and device/attack summaries.

## Archived Release
Zenodo: 
