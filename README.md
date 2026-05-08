# CPC3D Dataset

CPC3D is a controllable pose--clothing 3D body dataset for studying body shape estimation and anthropometric measurement under clothing from 3D scans.

The dataset is designed to support controlled analysis of how human posture and garment type affect body shape estimation accuracy, regional error distribution, and measurement reliability.

## Dataset Overview

CPC3D contains approximately 4 million synthetic dressed point-cloud samples generated from SMPL bodies and realistic garments.

The dataset covers:

- 8 garment types
- 10 representative human poses
- 80 pose--clothing combinations

For each pose--clothing combination, the same body shape can be compared across different poses and clothing conditions. This design supports analysis of pose effects, clothing effects, and their interaction.

In addition to the synthetic dataset, CPC3D includes a small-scale real-scan subset with manual measurements. This subset supports measurement analysis by comparing measurements extracted from predicted SMPL bodies with manual references.

## What Will Be Released

This repository will provide the following resources upon paper acceptance.

### 1. Synthetic CPC3D Dataset

- Dressed partial point clouds
- Corresponding SMPL body ground truth
- Pose labels for P1--P10
- Clothing labels for the 8 garment types
- Training and testing sample lists used in the paper
- Sample information, including pose ID, clothing type, gender, and body-shape ID

### 2. Real-Scan Subset

- Small-scale real clothed scan data
- Ten-pose scans for each real subject
- Manual measurement references
- Subject and scan information, including clothing type and scanning posture

### 3. Measurement Definitions

- Predefined girth measurement paths on the template SMPL body
- Predefined distance measurement paths on the template SMPL body
- Scripts for transferring measurement paths to predicted SMPL bodies
- Scripts for extracting anthropometric measurements

### 4. Evaluation and Analysis Code

- BodyPointNet evaluation scripts
- Global L2 error computation
- Body-part L2 error computation
- Measurement error computation
- Linear mixed-effects model analysis scripts
- Scripts for reproducing the main tables and figures in the paper

## Dataset Release

The CPC3D dataset, real-scan subset, measurement definitions, and associated analysis code will be publicly released upon acceptance of the corresponding paper.

Paper: *CPC3D: A 4-Million-Sample Benchmark Dataset for Analyzing the Effects of Posture on Body Shape Estimation Under Clothing*

More details about the dataset generation pipeline, measurement definitions, and evaluation protocol can be found in the paper.

## Citation

The citation will be updated after publication.

## Contact

For questions about the dataset, please contact the authors through the corresponding paper.

Thank you for your interest in CPC3D.
