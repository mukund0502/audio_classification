# Audio Classification Project Readme

## Overview

This project focuses on audio classification using machine learning techniques. The goal is to accurately classify audio samples into one of the ten predefined categories.

### Categories and Sample Counts

1. **dog_bark**: 1000 samples
2. **children_playing**: 1000 samples
3. **air_conditioner**: 1000 samples
4. **street_music**: 1000 samples
5. **engine_idling**: 1000 samples
6. **jackhammer**: 1000 samples
7. **drilling**: 1000 samples
8. **siren**: 929 samples
9. **car_horn**: 429 samples
10. **gun_shot**: 374 samples

## Libraries Used

- **Librosa**: Used for audio preprocessing.
- **TensorFlow**: Employed for building the machine learning model.
- **Pandas**: Utilized for data manipulation and analysis.
- **NumPy**: Employed for numerical operations.
- **Scikit-learn**: Used for various machine learning utilities.

## Model and Training

The model architecture is implemented using TensorFlow, leveraging deep learning techniques for audio classification. Data preprocessing is conducted using librosa to extract relevant audio features.

### Training Process

The training process involves optimizing the model to minimize the classification loss. The hyperparameters, architecture, and training parameters are tuned for optimal performance.

## Test Accuracy

After training, the model achieves a test accuracy of approximately 84.49%, reflecting its ability to correctly classify audio samples from unseen data.

## Instructions for Replication

To replicate the project:

1. Clone repo using `git clone https://github.com/mukund0502/audio_classification.git`.
1. Install the required libraries.
1. Download complete dataset from [given link](https://urbansounddataset.weebly.com/download-urbansound8k.html). You can directly use final dataset provided in this repo named `final_dataframe.csv` after all preprocessing.
2. Ensure the dataset is structured as specified in the project, with the correct number of samples for each category.
3. Run the provided training script to train the model.
4. Evaluate the model on the test set to obtain accuracy metrics.

Feel free to explore and experiment with different architectures, hyperparameters, and preprocessing techniques to enhance the model's performance.

## Contact

If you have any questions or feedback, feel free to contact me. 

Happy coding!
