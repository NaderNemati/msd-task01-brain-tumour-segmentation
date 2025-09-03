# Brain-Tumour Segmentation — MSD Task01

This repo tackles Medical Segmentation Decathlon (Task01: Brain Tumour) using multi-modal MRI (FLAIR, T1, T1ce, T2). The goal is to segment tumour sub-regions (necrotic/non-enhancing core, edema, enhancing tumour) or a whole-tumour baseline. It includes a clean baseline built around U-Net (current: 2D binary whole-tumour; extensible to multi-class 3D U-Net), with NIfTI I/O, preprocessing, training/validation loops, and quick visualizations.

Dataset: MSD Task01 BrainTumour (NIfTI volumes).

Objective: pixel-wise tumour segmentation (WT / sub-regions).

Method: U-Net baselines (2D sigmoid; optional 3D softmax).

Outputs: predicted masks, overlays, and metrics (Dice, optional HD95).

Acknowledgements: Medical Segmentation Decathlon / BraTS.
