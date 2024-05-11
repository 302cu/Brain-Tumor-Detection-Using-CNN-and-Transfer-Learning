# Brain-Tumor-Detection-CNN
## Project Overview
This project develops a machine learning model capable of detecting brain tumors from MRI images. Utilizing the ResNet50V2 architecture with transfer learning, the model emphasizes high accuracy and efficiency in medical image analysis.

## Features
- **Data Preprocessing**: Adaptation of image data for effective machine learning application, including resizing and normalization.
- **Transfer Learning**: Implementation of the ResNet50V2 model for feature extraction.
- **Model Training**: Incorporates a custom classifier on top of ResNet50V2 to distinguish between normal and tumor images.
- **Evaluation**: Extensive testing to achieve high accuracy, with measures for overfitting through techniques like EarlyStopping and ReduceLROnPlateau.

## Getting Started
Follow these instructions to set up the project locally:

### Prerequisites
- Python 3.11.9 or higher
- pip

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/302cu/Brain-Tumor-Detection-CNN.git
2. Install required packages:
     pip install -r requirements.txt
### Usage
Execute the following command to start the Jupyter notebook:
  jupyter notebook
  Navigate to notebooks/ and open the relevant notebook to train the model.

## Model
The model integrates the ResNet50V2 base for robust feature extraction from MRI images, paired with a dense classifier to accurately predict the presence of brain tumors. The approach is fine-tuned for handling unbalanced medical image datasets.

## Results
The model achieved a training accuracy of 99.32% and a validation accuracy of 97.67%, demonstrating its potential for clinical use in early and accurate brain tumor detection.

## Contributing
We welcome contributions to improve the model and its applications. Follow standard fork and pull request procedures to contribute.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Abdullah Aldosari- [LinkedIn Profile](https://www.linkedin.com/in/abdullah-aldosari-058211239?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) - reff302@gmail.com
## Project Link
[Brain Tumor Detection CNN](https://github.com/302cu/Brain-Tumor-Detection-CNN)

## Acknowledgements
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

