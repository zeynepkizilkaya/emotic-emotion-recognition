# Training Scripts

This directory contains training scripts for both models.

**Note:** The main training pipeline is in `notebooks/Project_code.ipynb` (Google Colab notebook). These standalone Python scripts are provided for local training or custom experiments.

## For Google Colab Users:

Simply open `notebooks/Project_code.ipynb` in Colab and run all cells.

## For Local Training:

Use the scripts below...

# Training Scripts

This directory contains training scripts for both models.

## Files:

- **train_model1.py** - Training script for Model 1 (Two-stream baseline)
- **train_model2.py** - Training script for Model 2 (Three-stream with pose)
- **utils.py** - Utility functions for data loading and training

## Usage:

### Train Model 1:
```bash
python training/train_model1.py --epochs 20 --batch_size 16 --lr 1e-4
```

### Train Model 2:
```bash
python training/train_model2.py --epochs 10 --batch_size 16 --lr 5e-5
```

## Configuration:

Edit hyperparameters directly in the training scripts or pass as command-line arguments.

**Default Settings:**
- Optimizer: Adam
- Loss: Binary Cross-Entropy
- Batch size: 16
- Weight decay: 1e-5
- Data augmentation: Random flip + Color jitter
- # Training Scripts




