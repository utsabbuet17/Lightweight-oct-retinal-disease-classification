# Lightweight CNN Baseline for Retinal OCT Disease Classification

This repository provides a simple, reader-friendly baseline notebook for retinal disease classification from Optical Coherence Tomography (OCT) images.

The notebook is associated with the following paper:

> Utsab Saha, Puja Saha, MD Jahin Alam, and Maruf Ahmed, **Toward Efficient Identification of Retinal Diseases: A Lightweight Convolutional Neural Network-Based Approach Using Optical Coherence Tomography**, *Healthcare Technology Letters*, 2026. DOI: `https://doi.org/10.1049/htl2.70059`

## Repository content

```text
.
├── notebooks/
│   └── OCT_Lightweight_CNN_baseline_annotated.ipynb
├── README.md
```

## What this repository contains

- A baseline PyTorch implementation for OCT image classification.
- Human-readable markdown explanations added around the original code cells.


## Dataset format

The notebook uses `torchvision.datasets.ImageFolder`, so the dataset should follow this structure:

```text
OCT2017/
├── train/
│   ├── CNV/
│   ├── DME/
│   ├── DRUSEN/
│   └── NORMAL/
├── val/
│   ├── CNV/
│   ├── DME/
│   ├── DRUSEN/
│   └── NORMAL/
└── test/
    ├── CNV/
    ├── DME/
    ├── DRUSEN/
    └── NORMAL/
```

## How to use

1. Open the notebook in Kaggle, Google Colab, Jupyter Notebook, or JupyterLab.
2. Update the dataset path if needed.
3. Update the saved weight path if you want to load pretrained weights.
4. Run the notebook cells in order.

## Important note

The notebook currently contains Kaggle-style paths. These paths will not work automatically on every computer. Please update the paths according to your own dataset location.

## Citation

If this notebook or paper helps your work, please cite:

```bibtex
@article{saha2026toward,
  title={Toward Efficient Identification of Retinal Diseases: A Lightweight Convolutional Neural Network-Based Approach Using Optical Coherence Tomography},
  author={Saha, Utsab and Saha, Puja and Alam, MD Jahin and Ahmed, Maruf},
  journal={Healthcare Technology Letters},
  volume={13},
  number={1},
  pages={e70059},
  year={2026},
  publisher={Wiley Online Library}
}
```
