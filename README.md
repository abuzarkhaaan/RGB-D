# RGB-D IoT Small-Object Segmentation

This repository contains the official implementation and experimental artifacts for an IoT-grade RGB and depth (RGB-D) small-object segmentation framework designed for indoor environments. The work focuses on robust multimodal perception under realistic sensing conditions, including low-light RGB, missing or noisy depth, and cross-modal misalignment.

The proposed approach combines deterministic data auditing with a dual-encoder Vision Transformer (ViT) architecture and cross-attention fusion using a learnable residual gate. A leakage-safe, site-disjoint evaluation protocol is adopted, and robustness is systematically assessed under controlled RGB and depth degradations, together with explainability analysis and edge-oriented profiling.

The repository provides scripts and notebooks to reproduce preprocessing, training, evaluation, robustness testing, and deployment profiling. All reported figures, tables, and metrics in the paper are generated using this pipeline, supporting transparent and reproducible indoor IoT perception research.
