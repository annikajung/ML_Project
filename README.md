# Image Classification with TensorFlow/Keras

This project implements an image classification model using TensorFlow and Keras. The model is trained to classify images into four categories: blue, red, white, and fail.

## Prerequisites

- Python 3.9-3.11 
- pip (Python package installer)
- Virtual environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/annikajung/ML_Project.git
cd ML_Project
```

2. Create and activate a virtual environment:

On Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

On macOS/Linux:
```bash
python -m venv venv
source venv/bin/activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```


## Running the Notebook

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to the `notebook` folder and open `image_classification.ipynb`

3. Run the cells in order from top to bottom:


## Troubleshooting

Common issues and solutions:

1. **Memory Error**: Reduce batch_size or image_size in the notebook
2. **GPU Issues**: Check TensorFlow GPU support and CUDA installation
3. **Import Errors**: Ensure all requirements are installed correctly



## Contact

# Image Classification with TensorFlow/Keras

This project implements an image classification model using TensorFlow and Keras. The model is trained to classify images into four categories: blue, red, white, and fail.

## Prerequisites

- Python 3.9-3.11 (3.10 recommended)
- pip (Python package installer)
- Virtual environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd [repository-name]
```

2. Create and activate a virtual environment:

On Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

On macOS/Linux:
```bash
python -m venv venv
source venv/bin/activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## Project Structure

```
project/
│
├── data/
│   ├── train_four_label/
│   │   ├── blue/
│   │   ├── red/
│   │   ├── white/
│   │   └── fail/
│   │
│   └── test_four_label/
│       ├── blue/
│       ├── red/
│       ├── white/
│       └── fail/
│
├── notebook/
│   └── image_classification.ipynb
│
├── requirements.txt
└── README.md
```

## Data Preparation

1. Organize your images in the following structure:
   - Place training images in `data/train_four_label/[class_name]/`
   - Place test images in `data/test_four_label/[class_name]/`
   - Each class should be in its own folder (blue, red, white, fail)

2. Make sure all images are in a compatible format (jpg, png)

## Running the Notebook

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to the `notebook` folder and open `image_classification.ipynb`

3. Run the cells in order from top to bottom:
   - Setup and imports
   - Data loading and preprocessing
   - Model creation and training
   - Evaluation and analysis

## Notebook Sections

1. Setup and Imports
2. Set Random Seeds
3. Data Loading and Preprocessing
4. Data Analysis and Visualization
5. Data Preprocessing
6. Model Definition
7. Model Training
8. Model Evaluation
9. Detailed Analysis
10. Model Saving/Loading
11. Single Image Prediction

## Customization

To use the notebook with your own dataset:

1. Modify the `labels` list to match your categories:
```python
labels = ['your_class_1', 'your_class_2', ...]
```

2. Adjust the data paths:
```python
train_data_path = "path/to/your/train/data"
test_data_path = "path/to/your/test/data"
```

3. Optional: Modify model architecture in the `create_model` function

## Troubleshooting

Common issues and solutions:

1. **Memory Error**: Reduce batch_size or image_size in the notebook
2. **GPU Issues**: Check TensorFlow GPU support and CUDA installation
3. **Import Errors**: Ensure all requirements are installed correctly


## License

[Your License Information]

## Team

 - Annika Jung [Github](https://github.com/annikajung) 
 - Concetta Lanza [Github](https://github.com/lanzaco) 

