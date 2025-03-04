# README for Cross-Context Stress Detection Dataset

## Overview

This dataset is part of the research conducted for the paper titled "Cross-Context Stress Detection: Evaluating Machine Learning Models on Heterogeneous Stress Scenarios Using EEG Signals." It provides EEG data recorded from five participants under two distinct stress-inducing scenarios: mental arithmetic evaluation (MAE) and virtual reality (VR) gaming. The dataset is shared to enable further exploration of stress detection systems using machine learning (ML) and EEG data in cross-context scenarios.

## Dataset Description

The dataset includes EEG recordings collected using the MUSE-S™ EEG headband during stress-inducing tasks. The data is split into two categories:
1. **MAE-based stress data**: Data collected while participants performed mental arithmetic tasks.
2. **VR-based stress data**: Data collected while participants engaged in a rhythm-based VR game (Beat Saber™).

The EEG signals are pre-processed using wavelet denoising, with features extracted from both time and frequency domains. The dataset includes annotations indicating stress and relaxation states.

### Data Format

The dataset is provided in the following format:

- **EEG Signals**: Each file contains EEG data captured from multiple electrodes (AF7, AF8, TP9, TP10) during the stress induction tasks.
- **Labels**: Each EEG recording is labeled as either "stress" or "relaxation."
- **File Format**: Data is provided as MAT files.
<!-- - **Feature Extraction**: Additional files containing derived features from time-frequency analysis (e.g., median frequency, power spectral moments, etc.). -->

<!-- ### Columns in EEG Data --> 

<!-- - **Timestamp**: The time at which each data point was recorded. --> 
<!-- - **Electrode Data**: Signal readings from each electrode (AF7, AF8, TP9, TP10). --> 
<!-- - **Labels**: Stress/relaxation labels for each signal segment. --> 

## Data Acquisition

The data was collected from 5 undergraduate male participants (ages 19-22) from the Arab Academy for Science, Technology, and Maritime Transport (AASTMT). The study adhered to ethical guidelines, and informed consent was obtained from each participant.

### Stress Induction Protocols
1. **Mental Arithmetic Evaluation (MAE)**: Participants performed arithmetic problems under time constraints to induce cognitive stress.
2. **VR Gaming**: Participants engaged in a rhythm-based VR game, Beat Saber™, to induce stress.

### Equipment Used
- **EEG Headset**: MUSE S™ EEG headbands.
- **VR Headset**: Oculus Quest™ for the VR stress scenario.

## Usage

This dataset is intended for research on cross-context stress detection and ML-based models for stress classification. You may use this dataset to explore various ML models (e.g., SVM, LDA, KNN) and denoising techniques for EEG signal processing and stress detection.

### Citation

Please cite the following papers if you use this dataset in your research:

- Attallah, O., Mamdouh, M., & Al-Kabbany, A. (2025). Cross-Context Stress Detection: Evaluating Machine Learning Models on Heterogeneous Stress Scenarios Using EEG Signals, Submitted to MDPI AI.
- Mamdouh, M., Mahmoud, R., Attallah, O. and Al-Kabbany, A., 2023, May. Stress Detection in the Wild: On the Impact of Cross-Training on Mental State Detection. In 2023 40th National Radio Science Conference (NRSC) (Vol. 1, pp. 150-158). IEEE.

## License

This dataset is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt the dataset as long as appropriate credit is given, and any changes are indicated.

## Contact

For further questions, please contact:
- Omneya Attallah: o.attallah@aast.edu
- Ahmad Al-Kabbany: alkabbany@aast.edu

## Acknowledgments

- We would like to acknowledge the participants in the study for their involvement and the institutions that supported this research.
- The authors extend their heartfelt gratitude to Rojaina Mahmoud for her invaluable effort and dedication in data acquisition. Her commitment was truly inspiring and greatly appreciated, making this research possible.

---
