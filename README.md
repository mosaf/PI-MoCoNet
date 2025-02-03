# <p align=center>`PI-MoCoNet: A Physics-Informed Deep Learning Framework for Brain MRI Motion Artifact Correction`</p> # 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


:fire::fire:**PI-MoCoNet** is a deep learning framework designed to robustly remove motion artifacts in brain MRI images by integrating complementary information from both the spatial and *k*-space domains. 

## 🔄 Flowchart Overview

The following flowchart illustrates the architecture of **PI-MoCoNet**:

<p align="center">
  <img src="./images/flowchart.svg" alt="PI-MoCoNet Flowchart" style="width: 100%;">
</p>


## Getting Started

### Prerequisites

- Python (>=3.12)
- PyTorch (>=2.5)
- NVIDIA CUDA (for GPU acceleration)
- Additional dependencies as listed in `requirements.txt`

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mosaf/PI-MoCoNet.git
   cd PI-MoCoNet
   
2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt


## 📚 Citation

If you find **PI-MoCoNet** useful for your research or project, please consider citing our work:

<pre>
@article{yourcitation2025,
  title     = {A Physics-Informed Deep Learning Model for MRI Brain Motion Correction},
  author    = {Mojtaba Safari, Shansong Wang, Zach Eidex, Xiofeng Yang},
  journal   = {Journal Name},
  year      = {2025},
  publisher = {Publisher},
  doi       = {10.xxxx/xxxxxxxx}
}
</pre>

Alternatively, you can download the BibTeX citation file directly:

[📄 **Download BibTeX citation**](./citation.bib)

