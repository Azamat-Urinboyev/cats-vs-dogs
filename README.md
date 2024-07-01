# Cats vs Dogs Image Classification

This project involves building a machine learning model to classify images of cats and dogs using a convolutional neural network (CNN). The dataset used for training and testing the model is from the [Kaggle Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats).

## Project Structure

- `cats_vs_dogs.ipynb`: Jupyter notebook containing the code for data loading, preprocessing, model building, training, and evaluation.
- `dogs-vs-cats/`: Directory containing the dataset files.

## Requirements

- Python 3.x
- Libraries:
  - numpy
  - pandas
  - keras
  - sklearn
  - matplotlib
  - google.colab (for file uploads in Google Colab)

You can install the required libraries using `pip`:
```sh
pip install numpy pandas keras scikit-learn     matplotlib
```

## Dataset

The dataset can be downloaded from the [Kaggle Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats). Make sure to place the dataset files in the dogs-vs-cats/ directory. 

## Usage

### 1. Clone the repository:
```
    git clone https://github.com/yourusername/cats_vs_dogs.git
    cd cats_vs_dogs
```

### 2. Run the Jupyter Notebook:
```
    jupyter notebook cats_vs_dogs.ipynb
```

### 3. Follow the steps in the notebook:

- Import necessary libraries.
- Upload and prepare the dataset.
- Define image properties.
- Build and train the CNN model.
- Evaluate the model performance.


## Results

The model achieves an accuracy of approximately 98% on the test set.

## Acknowledgments

[Kaggle](https://www.kaggle.com/) for providing the dataset.

[Google Colab](https://colab.google/) for providing a free and convenient platform for running Jupyter notebooks.