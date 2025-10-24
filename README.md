<h1 align="center"><strong>SCADataset</strong></h1>

<p align="left">
  🪪&nbsp;<a href="#about">About</a>
  | 🏷️&nbsp;<a href="#dataset-description">Description</a>
  | 🗃️&nbsp;<a href="#Usage">Usage</a>
  | 🔗&nbsp;<a href="#citation">Citation</a>
  | 📝&nbsp;<a href="https://www.preprints.org/manuscript/202505.1150/v1" target="_blank">Paper</a>
</p>

This repository contains the dataset for the paper:
[Evaluating the Vulnerability of Hiding Techniques in Cyber-Physical Systems Against Deep Learning-Based Side-Channel Attacks](https://www.preprints.org/manuscript/202505.1150/v1)

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

## Usage
This dataset can be used for the following research and analysis purposes:
1. Analyzing the vulnerability of hiding techniques to side-channel attacks.
2. Training machine learning models for side-channel analysis.
3. Studying power consumption patterns of cryptographic algorithms.

## Citation
If you use this dataset for your research, please cite the following paper.
>Title: Evaluating the Vulnerability of Hiding Techniques in Cyber-Physical Systems Against Deep Learning-Based Side-Channel Attacks \
>DOI: [10.20944/preprints202505.1150.v1](https://www.preprints.org/manuscript/202505.1150/v1) (Preprint)
```bibtex
@article{park2025evaluating,
  journal = {Applied Sciences},
  title = {Evaluating the Vulnerability of Hiding Techniques in Cyber-Physical Systems Against Deep Learning-Based Side-Channel Attacks},
  doi = {https://www.mdpi.com/2076-3417/15/13/6981},
  author = {Park, Seungun and Seo, Aria and Cheong, Muyoung and Kim, Hyunsu and Kim, JaeCheol and Son, Yunsik},
  year = {2025}
}
```

<p align="center">
  <a href="https://plass.dongguk.edu" target="_blank">
    <img src="https://github.com/sucystem/PLASS/blob/main/logo.png" width="400" alt="PLASS Lab, Dongguk University">
  </a>
</p>
