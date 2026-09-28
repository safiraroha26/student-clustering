# Student Performance Clustering

A machine learning project that uses K-Means Clustering to analyze
student performance patterns based on study hours, attendance,
assignment scores, and exam scores.

## Project Overview

This project applies unsupervised learning to group students based
on similarities in their academic performance and learning-related
features.

The clustering results are then compared with students' graduation
status to analyze the characteristics of each cluster.

## Dataset

The dataset contains the following features:

- Jam Belajar
- Kehadiran
- Nilai Tugas
- Nilai Ujian

Target/reference variable:

- Status Lulus

Note: `Status_Lulus` is not used as a feature for clustering. It is
only used to compare the resulting clusters.

## Method

The project uses:

- Data loading
- Data cleaning
- Feature selection
- Feature standardization
- K-Means Clustering
- Cluster analysis
- Cluster comparison
- Data visualization

Two clustering configurations are compared:

- K = 2
- K = 3

## Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

## Analysis

For each clustering configuration, the project analyzes:

- Average study hours
- Average attendance
- Average assignment score
- Average exam score
- Comparison between clusters and graduation status

## Visualization

The clustering results are visualized using:

- Study Hours
- Exam Score

as the X and Y axes, with different colors representing each cluster.

## Project Workflow

Data
↓
Data Cleaning
↓
Feature Selection
↓
Standardization
↓
K-Means Clustering
↓
K = 2 / K = 3
↓
Cluster Analysis
↓
Comparison with Graduation Status
↓
Visualization

## Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YtCilKE2Yej9Pt_BiewBihN1G9btz5Si?usp=sharing)
