
# MRI Brain Tumor Classification using EfficientNet, ResNet101, and Xception

## Overview

This repository contains Jupyter Notebooks that implement MRI brain tumor classification using three state-of-the-art deep learning architectures: EfficientNetB3, ResNet101, and Xception. These models have been trained and evaluated to enhance the accuracy and efficiency of brain tumor diagnosis from MRI images.

## Repository Structure

```
├── EfficientnetB3 V1-Graph.ipynb  # Jupyter Notebook implementing EfficientNetB3 model
├── resnet101 V1-Graph.ipynb       # Jupyter Notebook implementing ResNet101 model
├── Xception V1-Graph.ipynb        # Jupyter Notebook implementing Xception model
├── README.md                      # Project README file
```

## Prerequisites

Before running the notebooks, ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- efficientnet
- Jupyter Notebook


## Usage

### Running the Notebooks

1. **Clone the Repository:**

   ```bash
   https://github.com/aasimghaffar/Enhancing-brain-tumor-diagnosis-by-elevating-MRI-image-classification.git
   cd Enhancing-brain-tumor-diagnosis-by-elevating-MRI-image-classification
   ```

2. **Launch Jupyter Notebook:**

   Start Jupyter Notebook in the project directory:

   ```bash
   jupyter notebook
   ```

3. **Select a Model Notebook:**

   Open any of the following notebooks to train and evaluate a specific model:
   
   - `EfficientnetB3 V1-Graph.ipynb`
   - `resnet101 V1-Graph.ipynb`
   - `Xception V1-Graph.ipynb`

4. **Run the Cells:**

   Follow the instructions within each notebook. The notebooks include all necessary steps, from data loading and preprocessing to model training, evaluation, and visualization of results.

### Data Preparation

Ensure that the MRI data is properly organized and available before running the notebooks. The data should be split into training, validation, and testing sets, with appropriate directories for each class (e.g., `tumor` and `no_tumor`). Modify the data paths in the notebooks as needed to point to your dataset location.

### Model Training and Evaluation

Each notebook follows these general steps:

- **Data Loading and Preprocessing:** Load the MRI images, preprocess them (e.g., resizing, normalization), and apply any necessary augmentations.
- **Model Architecture:** Define the architecture for the chosen model (EfficientNetB3, ResNet101, or Xception).
- **Training:** Train the model using the training dataset. The training parameters (e.g., epochs, batch size) can be adjusted within the notebook.
- **Evaluation:** Evaluate the model's performance on the validation and test datasets. Performance metrics such as accuracy, precision, recall, and F1-score are calculated.
- **Visualization:** Visualize training progress, model predictions, and confusion matrices to better understand model performance.

## Contributing

If you wish to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. Contributions are welcome, especially improvements in model performance or additional features.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact

For any questions or suggestions, please open an issue or contact me at [your-email@example.com].
