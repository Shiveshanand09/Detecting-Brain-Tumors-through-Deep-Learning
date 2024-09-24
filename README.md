# Brain Tumor Detection Project

This project involves detecting brain tumors using machine learning models applied to medical imaging data. The project uses image classification techniques to distinguish between different types of brain tumors, including glioma, meningioma, and pituitary tumors, as well as no tumor.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Brain tumor detection through medical imaging is crucial in early diagnosis and treatment. This project focuses on applying deep learning methods to classify MRI scans into four categories: glioma, meningioma, pituitary tumor, and no tumor. By training models on labeled MRI data, this project aims to achieve high accuracy in tumor detection.

## Dataset

The dataset consists of MRI brain scans, which are categorized into four classes:
- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

The dataset is divided into training and testing sets, each containing images from the aforementioned categories.

## Technologies Used

The following Python libraries and technologies are used in the project:
- **OpenCV**: For image processing and displaying images.
- **TensorFlow/Keras**: For building and training the deep learning model.
- **scikit-learn**: For model evaluation metrics and data splitting.
- **Google Colab**: For accessing datasets from Google Drive and running the model.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/brain-tumor-detection.git
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Make sure the dataset is stored in the correct path (`/content/drive/MyDrive/Brain_Tumor/`) or update the path in the notebook accordingly.

## Usage

1. Load the notebook in Google Colab or any Jupyter environment:

    ```bash
    jupyter notebook Brain_Tumor_Detection.ipynb
    ```

2. Make sure the dataset is properly linked from Google Drive. Mount the drive:

    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```

3. Run the notebook cells to:
    - Load and display brain tumor images.
    - Train a classification model using deep learning techniques.
    - Evaluate the model's accuracy.

### Example Output Images

The following images show examples from each tumor type as displayed in the notebook:

![Glioma Tumor](images/glioma_example.png)
*Glioma Tumor Sample*

![Meningioma Tumor](images/meningioma_example.png)
*Meningioma Tumor Sample*

![Pituitary Tumor](images/pituitary_example.png)
*Pituitary Tumor Sample*

![No Tumor](images/no_tumor_example.png)
*No Tumor Sample*

## Results

After training the model on the MRI dataset, the accuracy is evaluated using metrics like precision, recall, and F1-score. The model’s performance is assessed on a separate test set to ensure generalization.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements, bug fixes, or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
