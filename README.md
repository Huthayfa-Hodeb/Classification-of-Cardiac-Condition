# Cardiac Condition Classification

This project focuses on the classification of cardiac conditions using Deep Learning techniques. The system analyzes cardiac images to identify and classify various heart conditions, providing a valuable tool for medical diagnosis assistance.

## Project Structure

- `prepare-dataset.ipynb`: Notebook for data preparation and preprocessing
  - Handles image loading and preprocessing
  - Performs data augmentation
  - Splits data into training and validation sets
- `model-training.ipynb`: Notebook containing the model training pipeline
  - Implements the deep learning model architecture
  - Handles model training and validation
  - Includes performance evaluation metrics
- `Classification of Cardiac Conditions.pdf`: Project documentation and details

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
cd [repository-name]
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Getting Started

1. Ensure you have Python 3.x and Jupyter Notebook installed
2. Open the notebooks in order:
   - First run `prepare-dataset.ipynb` to prepare your dataset
   - Then run `model-training.ipynb` to train the model

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python packages:
  - numpy>=1.21.0
  - pandas>=1.3.0
  - opencv-python>=4.5.0
  - torch>=1.9.0
  - torchvision>=0.10.0
  - scikit-learn>=0.24.0
  - matplotlib>=3.4.0
  - seaborn>=0.11.0
  - Pillow>=8.0.0

## Usage

1. Data Preparation:
   - Place your cardiac images in the appropriate directory
   - Run `prepare-dataset.ipynb` to preprocess the images
   - The notebook will create the necessary training and validation sets

2. Model Training:
   - Run `model-training.ipynb` to train the model
   - The notebook includes visualization of training progress
   - Model checkpoints will be saved automatically
