This repository contains the official implementation of the paper
“Multi-scale Generative Modelling for Enhanced Sparse-View 3D Scene Reconstruction”,
submitted to The Visual Computer.
If you use this code, please cite the corresponding manuscript.

## Environment
- Python: 3.10
- CUDA: 12.1
- GPU: RTX 4090

## Dataset
DTU Dataset  
Split: 70 train / 15 val / 15 test  
Sparse views: 3, 5, 9

## Training
```bash
python train.py