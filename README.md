# Finetuning Deep Learning Models on Astrophysical Datasets

This repository contains code and a Jupyter notebook for finetuning deep learning models on the Galaxy Zoo astrophysical dataset using PyTorch and Hugging Face Transformers. The notebook demonstrates how to set up the dataset, train a ResNet model, and apply Parameter-Efficient Fine-Tuning (PEFT) techniques such as LoRA.

## Features
- Custom PyTorch `Dataset` class for Galaxy Zoo images and labels
- Data loading and train/test split
- Model initialization using Hugging Face's ResNet
- LoRA configuration for PEFT
- Training and evaluation functions
- Example usage for both standard and LoRA-based training

## Requirements
- Python 3.8+
- PyTorch
- torchvision
- transformers
- huggingface_hub
- peft
- tqdm
- pandas
- Pillow

Install dependencies in your notebook with:
```python
!pip install peft transformers torch torchvision huggingface_hub tqdm pandas Pillow
```

## Dataset
- Galaxy Zoo images and labels (CSV)
- Download and unzip the dataset files as shown in the notebook

## Usage
1. Place the dataset files in the appropriate directories as referenced in the notebook.
2. Open `notebook95755bc104.ipynb` in Jupyter or VS Code.
3. Run the cells sequentially to:
   - Install dependencies
   - Load and preprocess data
   - Initialize and train the model
   - Evaluate performance
   - Apply LoRA for PEFT

## Notebook Structure
1. **Install dependencies**
2. **Import libraries**
3. **Define custom dataset class**
4. **Unzip and prepare data**
5. **Set up DataLoader and train/test split**
6. **Initialize model, loss, optimizer, and LoRA config**
7. **Define training and evaluation functions**
8. **Run training and evaluation (standard and LoRA)**

## Notes
- The notebook is designed for use in environments like Kaggle or local Jupyter setups.
- Update file paths as needed for your environment.
- Example code for Hugging Face Hub login is included but commented out.

## License
This project is licensed under the MIT License.
