# Developing a Convolutional Neural Network for Bird Call Identification: A Case Study at Intaka Island

## Overview
This repository contains the code and resources related to the development of a Convolutional Neural Network (CNN) for identifying bird calls at Intaka Island. The project focuses on leveraging machine learning techniques to analyze audio data and detect bird calls, contributing to ecological research and wildlife monitoring efforts. The whole dataset used to trained the model can be accessed under request to the AIMS, South Africa, AI students.

## Repository Structure
- **Data/**: This directory stores my unique audio datasets and the annotated files of each recording.
- **Predictions/**: This directory holds all predicted labels for the whole test files.

## Usage
To use the code in this repository, follow these steps:
1. Clone the repository to your local machine.
2. Load the saved model `model3.keras`.
3. Run the main script `predict.py` to make prediction on the audio files.
4. Once done, check all CSV files containing all predicted labels on your working directory.
5. Compare them with each annotated files.

## Dependencies
The code in this repository requires the following dependencies:
- Python 3.x
- Librosa
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Reference
- Jeantet, L., Dufourq, E., 2023. Improving deep learning acoustic classifiers with contextual information for wildlife monitoring. Ecological Informatics, 77, 102256.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
