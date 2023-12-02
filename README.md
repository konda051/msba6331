# MSBA6331 - Trends Market Place - Big Data Analytics Project: Leveraging Hugging Face's Pre-Trained Models for Advanced Text Classification

This repository houses the code and resources for our project on advanced text classification using Spark NLP, completed in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.

## Project Overview

This project is designed to critically assess and compare the efficacy of Spark NLP 5.1.4 and Hugging Face's Transformers in applying and fine-tuning pre-trained BERT models for text classification tasks. By building and adjusting a BERT classification model using Spark NLP and contrasting it with Hugging Face’s DistilBERT base uncased model, the study aims to evaluate their performance based on accuracy, precision, recall, and computational efficiency metrics. This comparison will shed light on the adaptability of these models to specific datasets and tasks, focusing on their minimal training requirements and resource optimization, particularly in GPU utilization and data processing techniques like batching.
The project's primary objective is to offer insights into the suitability of Spark NLP and Hugging Face Transformers for various applications in business analytics, emphasizing their strengths and limitations in real-world settings. The findings will guide practitioners in selecting the most appropriate NLP tools for their specific needs, thereby underscoring the practical applications and customization potential of advanced pre-trained models in the rapidly evolving domain of NLP


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

