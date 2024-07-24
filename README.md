# Iris Flower Classification

This project involves classifying Iris flowers into three species (Setosa, Versicolour, and Virginica) based on the features of the flowers using various machine learning models.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/iris-flower-classification.git
    cd iris-flower-classification
    ```

2. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook
    ```

2. Upload the Iris dataset using the provided code snippet in the notebook:
    ```python
    from google.colab import files

    # Upload the file
    uploaded = files.upload()

    # Get the name of the uploaded file
    file_name = list(uploaded.keys())[0]

    # Read the CSV file
    data = pd.read_csv(file_name)
    ```

3. Run the cells to see the results of different models.

## Dataset

The Iris dataset is a classic dataset used in machine learning and statistics. It includes 150 observations of iris flowers with four features: sepal length, sepal width, petal length, and petal width.

## Model Training

Three different models were used to classify the Iris dataset:
1. Support Vector Machine (SVM)
2. Logistic Regression
3. Decision Tree

The models were trained and tested using a 80-20 train-test split. The following steps were performed:
- Data loading and preprocessing
- Model training
- Model evaluation

## Results

The accuracy of the models on the test set were as follows:
- **SVM**: 96.67%
- **Logistic Regression**: 96.67%
- **Decision Tree**: 93.33%

The classification reports and confusion matrices are also included in the notebook for a detailed analysis.

## Contributing

Contributions are welcome! Please fork this repository and open a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
