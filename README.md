# Pharmaceutical Product Matching

This repository contains code for pharmaceutical product matching using machine learning models. The project includes training and testing notebooks, as well as a pre-trained model for ease of use.

## Features
- Pre-trained model for pharmaceutical product matching
- Training scripts to fine-tune models
- Easy-to-use inference scripts
- Uses Logistic Regression and TF-IDF for entity matching and similarity detection

## Installation
### Clone the repository
```sh
git clone https://github.com/Marwan513/Pharmaceutical-product-matching.git
cd Pharmaceutical-product-matching
```

### Install dependencies
```sh
pip install -r requirements.txt
```

## Download the Pre-Trained Models
The pre-trained models are hosted separately due to their size (>100MB). Download and extract them using:
```sh
wget https://github.com/Marwan513/Pharmaceutical-product-matching/releases/download/v1.0/models.zip
unzip models.zip -d models/
```

## Models Used
The models used in this project are based on Logistic Regression and TF-IDF (Term Frequency-Inverse Document Frequency) for entity matching and similarity detection. They have been fine-tuned for pharmaceutical product matching tasks.

## Usage
### Training
To train a model, run the `train_models.ipynb` notebook. The training dataset must be in a format similar to the Excel file in the repository (`Product Matching Dataset`).

### Testing
To test the model, run the `test_models.ipynb` notebook. The test dataset must be in a format similar to the `test file` in the repository. If not, it is recommended to modify the test file accordingly.

## Contributing
Feel free to submit issues and pull requests to improve this project.

## License
This project is licensed under the MIT License.

