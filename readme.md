# Techniques Applied
- Data Augmentation
- Train-test split with K-fold Cross Validation
- Voting vs Stacking Ensemble

# Models Used
- ViT
- CropNet

# Getting Started
Install PyTorch by following [this guide](https://pytorch.org/get-started/locally/). It should look something like:
```bash
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
```
If you need to find your CUDA version, you can run:
```bash
nvcc --version
```
Afterwards you can install the remaining dependencies:
```bash
conda install --yes --file requirements.txt
```