# CuttingEMD
An EMD tutorial for CuttingEEG Frankfurt 2023

This tutorial packages a subset of the tutorials from the [EMD documentation](https://emd.readthedocs.io/en/stable/index.html) alongside a specific example application using an EEG recording from the LEMON dataset.

## Requirements

The EMD documentation tutorials can run anywhere that EMD has been installed ([see here for installation instructions](https://emd.readthedocs.io/en/stable/install.html)). The CuttingEMD EEG application additionally requires [OSL](https://pypi.org/project/osl/) which can be installed with pip. All notebooks have `pip install` requirements in a commented cell at the top.


## Open interactive notebooks

You can run these tutorials where you link, but these links will open each tutorial in an interactive google colab session where you can run the code in-browser.

|  Colab Link  |  Tutorial  |
| - | --- |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ajquinn/CuttingEMD/blob/main/emd_tutorial_01_sift_01_siftintro.ipynb) | **Tutorial 1**: Introduction to sifting. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ajquinn/CuttingEMD/blob/main/emd_tutorial_01_sift_04_masksift.ipynb) |  **Tutorial 2**: Solving mode-mixing with mask sifting. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ajquinn/CuttingEMD/blob/main/emd_tutorial_02_spectrum_01_hilberthuang.ipynb) |  **Tutorial 3**: Instantaneous frequency and the Hilbert-Huang Transform. |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ajquinn/CuttingEMD/blob/main/CuttingEMD.ipynb) |  **CuttingEMD**: Simple EEG EMD analysis using a data from LEMON. |
