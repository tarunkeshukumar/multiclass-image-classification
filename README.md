# MultiClass Image Classification using CNN

This repository contains code for a multi-class image classification project using Convolutional Neural Networks (CNN). The project focuses on classifying images from the Intel Image Classification dataset into different categories.

## Dataset: Intel-image-classification

The Intel Image Classification [Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) contains images categorized into various classes, such as buildings, forests, mountains, etc. The dataset is used for training and evaluating the CNN model's performance.

## Model Performance

During training, the model achieved the following accuracy and loss metrics:

- Training Data Accuracy: 93.92%
- Validation Data Accuracy: 89.03%
- Validation Loss: 0.4049
- Learning Rate: 1.0000e-06
- Time per Epoch: 113 seconds

For the test data, the following results were obtained:

- Test Data Loss: 0.4049
- Test Data Accuracy: 89.03%
- Time per Step: 74ms

## Usage

1. Clone this repository:

   ```
   git clone https://github.com/your-username/multiclass-image-classification.git
   ```

2. Run the training script


3. To reproduce and track experiments, the code uses Comet.ml. Make sure to create a Comet.ml account and replace the necessary API keys in the code. For more information, refer to the official Comet.ml documentation.

4. Modify hyperparameters and model architecture to experiment and optimize performance.


## License

This project is licensed under the [MIT License](LICENSE).
