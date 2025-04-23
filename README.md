# SCADataset

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