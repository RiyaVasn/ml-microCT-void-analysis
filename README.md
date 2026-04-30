# Automated Micro-CT Image Segmentation and Void Analysis of HDPE-HGM Syntactic Foams using Machine Learning

Syntactic foams are a subclass of composite materials in which the matrix is embedded with hollow microspheres, offering a high strength-to-weight ratio suitable for the aerospace, marine, and automotive industries. The microspheres create porosity, visually indistinguishable from voids caused by manufacturing during imaging, both of which influence mechanical performance. Quantification and classification are, therefore, crucial for quality control and predictive modelling. This thesis proposes an integrated pipeline utilizing micro-CT imaging and unsupervised learning to segment and quantify voids, particles, and matrix in HDPE-HGM syntactic foams. A hybrid segmentation technique leveraging slice-wise thresholding and K-means clustering resulted in an F1 score of 0.92 compared to LabKit for voids. Voids were further classified into raster voids and HGM cavities based on shape descriptors, with subsequent spatial analysis performed using the R-index and clustering coefficients. Morphological features were correlated to Ultimate Tensile Strength and Young's Modulus. A custom GUI enables 3D visualization and segmented mesh export, facilitating the creation of digital twins for enhanced material analysis and process optimization.

## Graphical Abstract
![Graphical Abstract](https://github.com/user-attachments/assets/f3754364-e5cf-48df-8673-2b284c05251d)

## Project Overview

This repository introduces my master’s thesis, which explores an automated machine learning pipeline for segmenting and analyzing micro-CT images of 3D-printed syntactic foams. The research focuses on high-density polyethylene (HDPE) composites reinforced with hollow glass microspheres (HGMs), aiming to evaluate void structure and predict mechanical properties without destructive testing.

## Tools and Technologies

- Python (NumPy, OpenCV, Pandas, Matplotlib)
- Scikit-learn (K-means clustering, regression)
- PyVista (3D visualization)
- ImageJ (image validation)
- Micro-CT image processing (TIFF stacks)
- Jupyter Notebooks for exploratory analysis

## Methodology

The project applies unsupervised learning to segment grayscale CT images, extract morphological features such as void volume fraction and sphericity, and correlate them with tensile strength and modulus. The goal is to replace destructive mechanical testing with a scalable, image-based predictive pipeline. The codebase includes a lightweight standalone GUI software built using Python, designed to make segmentation and void analysis workflows accessible without writing code.
<img width="975" height="558" alt="image" src="https://github.com/user-attachments/assets/90720fe2-ebbb-4dfe-bca7-c452e8b44ae5" />


## Scope and Complexity

This work combines mechanical engineering, materials science, and computer vision. It handles large-scale image datasets (1,000+ slices per sample), reduces segmentation bias, and establishes a generalized framework for analyzing additively manufactured composite structures.

## Note

The complete code, data, and visualizations will be uploaded after formal publication. This repository currently documents the technical scope and research direction.

## Reference

**“Automated Segmentation of Voids and Particles in HDPE-HGM Syntactic Foams Using µCT Imaging and K-Means Clustering,”**  *Materials & Design*, Elsevier, 2025.  
[DOI](https://doi.org/10.1016/j.matdes.2026.115538)

