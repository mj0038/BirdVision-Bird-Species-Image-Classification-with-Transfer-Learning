# Bird Species Classification using VGG-16

This project focuses on classifying bird species using the VGG-16 model, a deep convolutional neural network. The model, enhanced through transfer learning with pre-trained weights from the ImageNet dataset, is fine-tuned to identify 20 distinct bird species. The project aims to showcase the efficacy of transfer learning in computer vision, particularly beneficial when the dataset is limited.

## Tech Stack
The project employs the following technologies and libraries:
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- Adam Optimizer (Keras)

## Project Structure
Files in the project:
- `main.py`: Python script for model construction, training, and evaluation.
- `main.ipynb`: Jupyter notebook offering an interactive approach to the project, including data exploration, model training, and visualization.
- `Classes.xlsx`: Excel file containing class mappings for bird species.
- `requirements.txt`: Lists libraries needed to run the project.

## Setup and Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/bird-species-classification.git
    cd bird-species-classification
    ```

2. **Create and Activate a Virtual Environment:**
    - For **Unix or MacOS**:
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```
    - For **Windows**:
        ```bash
        python -m venv venv
        .\venv\Scripts\activate
        ```

3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Running the Script or Notebook:**
    - For the script:
        ```bash
        python main.py
        ```
    - For the Jupyter notebook:
        ```bash
        jupyter notebook main.ipynb
        ```

## Model Training and Evaluation
- The `main.py` and `main.ipynb` encapsulate data loading, image preprocessing, VGG-16 model architecture setup, and model training.
- Model is compiled with categorical crossentropy as loss function and accuracy as metric.
- Adam optimizer is utilized for its efficiency and adaptive learning capabilities.
- `ModelCheckpoint` and `EarlyStopping` callbacks are integrated for optimal model saving and to curb overfitting.

The model's performance after training reflects an accuracy of 78.36% on the test dataset.

## Contributing
Feel free to contribute! You can fork the repository, make your changes, and create a pull request.

---
This README provides a detailed guide to getting the project up and running. It's structured to be clear and user-friendly, ensuring comprehensibility and ease of use for individuals at different levels of familiarity with the tech stack.
