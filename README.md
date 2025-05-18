<h1 align="center"><strong>SCADataset</strong></h1>

<p align="left">
  🪪&nbsp;<a href="#about">About</a>
  | 🏷️&nbsp;<a href="#dataset-description">Description</a>
  | 🪄&nbsp;<a href="#use-cases">Usecase</a>
  | 🔗&nbsp;<a href="#citation">Citation</a>
  | 📝&nbsp;<a href="https://www.preprints.org/manuscript/202505.1150/v1" target="_blank">Paper</a>
</p>

This repository contains the dataset for the paper:
<a href="https://www.preprints.org/manuscript/202505.1150/v1" target="_blank">Evaluating the Vulnerability of Hiding Techniques in Cyber-Physical Systems Against Deep Learning-Based Side-Channel Attacks</a>

## About
SCADataset is a dataset for Side-Channel Analysis (SCA) related to cryptographic algorithms. This dataset includes power consumption data during the execution of various cryptographic algorithms (DES, Hash, RSA) and can be utilized for research and analysis of side-channel analysis.

## Dataset Description
### Generation Tools
- Qemu
- GDB
- Elmo

### Column Description
- `Sequence`: A unique identifier representing the order of the data.
- `Power`: The power consumption value measured during the execution of cryptographic algorithms.
- `label`: The label of the data:
  - `0`: Original data
  - `1`: Dummy data
- `instruction`: The assembly instruction executed.
- `context`: Contextual information related to the cryptographic algorithm.

### Data Summary
- Total number of records: 832,555
- Cryptographic algorithms: DES, Hash, RSA
- Labels:
    - `0`: Original data
    - `1`: Dummy data

## Use Cases
This dataset can be used for the following research and analysis purposes:
1. Analyzing the vulnerability of hiding techniques to side-channel attacks.
2. Training machine learning models for side-channel analysis.
3. Studying power consumption patterns of cryptographic algorithms.

## Citation
If you find this data useful for your research, please cite the following work.
```bibtex
@article{park2025evalHiding,
  journal = {Preprints},
  title = {Evaluating the Vulnerability of Hiding Techniques in Cyber-Physical Systems Against Deep Learning-Based Side-Channel Attacks},
  doi = {10.20944/preprints202505.1150.v1},
  author = {Park, Seungun and Seo, Aria and Cheong, Muyoung and Kim, Hyunsu and Kim, JaeCheol and Son, Yunsik},
  year = {2025}
}
```

<p align="center">
  <a href="https://plass.dongguk.edu" target="_blank">
    <img src="https://github.com/sucystem/PLASS/blob/main/logo.png" width="400" alt="PLASS Lab, Dongguk University">
  </a>
</p>
