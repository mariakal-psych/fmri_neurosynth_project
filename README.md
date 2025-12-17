# Visualization of fMRI Data from Neurosynth

## Author
Maria Kalantzi  
13 December 2025

## Project Description
This project visualizes functional MRI (fMRI) meta-analysis data obtained from the
Neurosynth platform. The selected cognitive concept for this analysis is **chronic pain**.
A statistical brain map (uniformity test) is overlaid on an anatomical MRI scan to
highlight brain regions that are strongly associated with this concept. In addition,
a histogram is used to examine the distribution of functional activation values.

## Repository Contents
- `fmri_project.ipynb` – Jupyter notebook containing the full analysis and visualizations
- `anatomical.nii.gz` – Anatomical MRI scan
- `chronic_pain_uniformity-test_z_FDR_0.01.nii.gz` – Functional statistical map from Neurosynth
- `pull_request_screenshot.png` – Screenshot of submitted pull request comments

## Python Packages Used
- Python 3
- numpy
- nibabel
- nilearn
- matplotlib

## Data Source
Neurosynth Meta-Analysis (Chronic Pain):  
https://neurosynth.org/analyses/terms/chronic%20pain
