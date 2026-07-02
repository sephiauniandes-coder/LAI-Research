# LAI-Research
SURF Purdue Project (2026): Fusing UAV-based hyperspectral and LiDAR remote sensing to improve Leaf Area Index (LAI) estimation in maize.

This project extends an existing UAV-based framework (Quijano, 2026) that uses spectral (hyperspectral) and structural (LiDAR) features to estimate LAI, testing whether the approach generalizes to new corn hybrids and a new growing season. Field data are collected during the 2026 growing season at Purdue's Agronomy Center for Research and Education (ACRE, Field 58) on two corn hybrids of contrasting height (DKC62-70, tall; PR113-60, short). Ground-reference LAI is measured weekly with a handheld plant canopy analyzer (LAI-2200C), while UAV-based hyperspectral and LiDAR imagery are collected over the same plots.

Vegetation indices and structural features extracted from the UAV imagery are reduced using Recursive Feature Elimination (RFE-CV) and used to train and cross-validate a Support Vector Regression (SVR-RBF) model. Where appropriate, the 2026 data are combined with an existing 2023 dataset to increase the sample size available for model development.
