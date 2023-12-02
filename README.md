# MSBA6331 - Trends Market Place - Big Data Analytics Project: Leveraging Hugging Face's Pre-Trained Models for Advanced Text Classification

This repository houses the code and resources for our project on advanced text classification using Spark NLP, completed in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.

## Project Overview

Our project aims to leverage the state-of-the-art Natural Language Processing (NLP) capabilities provided by Spark NLP to perform text classification tasks. Specifically, we use the pre-trained BERT (Bidirectional Encoder Representations from Transformers) model for classifying SMS messages as spam or not spam.

## Repository Contents

- `Bertclassification_final.ipynb`: Jupyter notebook with the Spark NLP code for text classification.
- `README.md`: This file, serving as the project homepage and executive summary.

## Quick Links

- [Project Video](#)
- [Project Flier](#)
- [Dataset Source](https://archive.ics.uci.edu/ml/machine-learning-databases/00228/smsspamcollection.zip)
- [Additional Resources](#)

## Getting Started

To reuse and run this project's code, please follow the setup instructions below.

### Prerequisites

- Apache Spark version 3.2.3
- Spark NLP version 5.1.4
- An environment capable of running Jupyter notebooks

### Installation and Setup

1. Ensure that Apache Spark 3.2.3 is installed and properly configured on your system.
2. Install Spark NLP 5.1.4 by running `pip install spark-nlp==5.1.4`.
3. Download the dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/00228/smsspamcollection.zip) and extract the contents.
4. Start a Jupyter notebook server in the environment where Spark and Spark NLP are installed.
5. Open the `Bertclassification_final.ipynb` notebook.

### Running the Notebook

Execute each cell in the Jupyter notebook in order. The main steps are:

- Initializing Spark NLP components
- Building and fitting the classification pipeline
- Evaluating model performance

The expected output is the accuracy of the SMS spam classification model.

## Support

For any additional information or support, please raise an issue in the repository or contact the contributors.

## Contributors

- [Contributor 1](#)
- [Contributor 2](#)
- [Contributor 3](#)
- [Contributor 4](#)

## License

This project is licensed under the [MIT License](LICENSE.md).

