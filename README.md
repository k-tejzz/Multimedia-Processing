# Multimedia Processing

A collection of laboratory experiments in digital image processing, implemented in Python. The project covers core techniques including color quantization, spatial and frequency-domain sampling, high dynamic range (HDR) imaging, spatial filtering, and bit-plane slicing.

## Overview

This repository contains six independent experiments developed for a Multimedia Processing course. Each experiment is implemented from first principles to demonstrate the underlying algorithm, rather than relying solely on high-level library functions. Together, they explore how different processing techniques affect image quality, compression, and visual representation.

## Contents

| Experiment | Topic | Techniques |
|---|---|---|
| [Q1](./Q1) | Image Quantization | Greyscale via desaturation, median cut quantization, octree quantization |
| [Q2](./Q2) | K-Means Rate-Distortion Quantization | K-Means clustering, codebook generation, rate-distortion optimization |
| [Q3](./Q3) | Frequency & Spatial Sampling | FFT-based sampling, spatial subsampling, comparison across sampling factors |
| [Q4](./Q4) | High Dynamic Range (HDR) Imaging | Camera response function recovery, irradiance map reconstruction, tone mapping |
| [Q5](./Q5) | Spatial Filtering | Box filters (5×5, 20×20), Gaussian and normalized Gaussian filters |
| [Q6](./Q6) | Bit-Plane Slicing | Bit-plane extraction, image reconstruction, difference imaging |

## Repository Structure

```
Multimedia-Processing/
├── Presentation/
│   └── Multimedia Processing.pptx
├── Q1/
├── Q2/
├── Q3/
├── Q4/
├── Q5/
├── Q6/
├── requirements.txt
└── README.md
```

## Technologies

- Python 3
- NumPy
- Pillow (PIL)
- OpenCV
- Matplotlib

## Setup

Clone the repository and install dependencies:

```bash
git clone https://github.com/k-tejzz/Multimedia-Processing.git
cd Multimedia-Processing
pip install -r requirements.txt
```

## Usage

Each experiment is self-contained within its respective directory. To run one, navigate to the folder and execute its script:

```bash
cd Q1
python code.py
```

Repeat for `Q2` through `Q6` as needed.

## Course

Multimedia Processing Laboratory

## Author

**K. Sathya Teja**
GitHub: [@k-tejzz](https://github.com/k-tejzz)

## Acknowledgements

Developed for academic and educational purposes. References used in each experiment are documented in the accompanying presentation.
