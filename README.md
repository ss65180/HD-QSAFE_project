# HD-QSAFE_project
HD-QSAFE Quantum Image Representation Research Implementation

HD-QSAFE: Hierarchical and Dynamic Quantum-Safe Adaptive Feature Encoding

HD-QSAFE is a research-oriented quantum image representation framework designed to address the scalability, fidelity, and resource limitations of existing Quantum Image Representation (QIR) techniques.

This repository provides the complete implementation, preprocessing pipeline, encoding methodology, evaluation metrics, and visualization tools used to validate the HD-QSAFE framework on medical and remote sensing imagery.

Project Overview:

Quantum image representation is a key component of quantum machine learning and quantum image processing. Traditional QIR models often suffer from:

High qubit requirements
Large circuit depths
Poor scalability for high-resolution images
Information loss during encoding

HD-QSAFE introduces a hierarchical and adaptive encoding strategy that improves efficiency while preserving image fidelity.

Key Features:
Conversion of MRI .mat datasets into image format
Hierarchical block-based feature extraction
Adaptive feature importance selection
Quantum state encoding using Qiskit
Quantum image reconstruction from statevector probabilities


Quantitative evaluation using:
Fidelity
PSNR (Peak Signal-to-Noise Ratio)
KL Divergence
Entropy Difference


Automated generation of research-grade visualizations:
Performance comparison heatmaps
Quantum resource usage charts
Encoding time scalability graphs
Reconstruction difference heatmaps

Repository Structure
hd-qsafe-quantum-image/
│
├── hd_qsafe_pipeline.py      Main implementation of HD-QSAFE
├── requirements.txt          Required Python dependencies
├── README.md                 Project documentation
├── sample_outputs/           Generated plots and result images
└── data/                     Dataset directory (not included)

Installation

Ensure Python 3.9 or later is installed.

git clone https://github.com/YOUR_USERNAME/hd-qsafe-quantum-image.git
cd hd-qsafe-quantum-image
pip install -r requirements.txt

How to Run

Update dataset paths inside the script if needed, then execute:

python hd_qsafe_code.py


The pipeline will:
Convert MRI .mat files into image format
Perform HD-QSAFE encoding
Reconstruct quantum images
Compute performance metrics
Generate visual and statistical comparisons

Technologies Used:

Python:
Qiskit
NumPy
OpenCV
Matplotlib
Seaborn
SciPy

Datasets:

This implementation is compatible with:
Brain Tumor MRI datasets stored in .mat format
ICEYE SAR imagery for quantum remote sensing experiments
Datasets are not included in the repository due to size and licensing restrictions.

Research Contributions:

HD-QSAFE introduces:
Hierarchical feature compression to reduce qubit requirements
Adaptive feature selection based on local importance
Entropy-aware amplitude normalization
Improved scalability compared to FRQI, NEQR, MCQI, and related QIR methods

Citation:
If you use this repository for academic research, please cite:

HD-QSAFE: Hierarchical and Dynamic Quantum-Safe Adaptive Feature Encoding for Quantum Image Representation, 2026.


Author
Shweta Singh
Researcher in Quantum Image Processing and Machine Learning


Future Work:
Hybrid classical–quantum feature optimization
Noise-resilient encoding for NISQ devices
Deployment on real quantum hardware
