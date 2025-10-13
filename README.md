# Automated Micro-CT Image Segmentation and Void Analysis of HDPE-HGM Syntactic Foams using Machine Learning

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

The project applies unsupervised learning to segment grayscale CT images, extract morphological features such as void volume fraction and sphericity, and correlate them with tensile strength and modulus. The goal is to replace destructive mechanical testing with a scalable, image-based predictive pipeline.
<img width="975" height="558" alt="image" src="https://github.com/user-attachments/assets/90720fe2-ebbb-4dfe-bca7-c452e8b44ae5" />


## Scope and Complexity

This work combines mechanical engineering, materials science, and computer vision. It handles large-scale image datasets (1,000+ slices per sample), reduces segmentation bias, and establishes a generalized framework for analyzing additively manufactured composite structures.

## Note

The complete code, data, and visualizations will be uploaded after formal publication. This repository currently documents the technical scope and research direction.

## Reference

This project is based on research conducted at York University as part of my Master of Applied Science thesis in Mechanical Engineering (2025).
