# Smart Health Card

├── CNN_TESTING.py                # CNN model for health predictions
├── dataset.csv                   # Dataset used for ML models
├── dm.py                         # Data management for the project
├── Health_Doctor_excercise_diet.csv  # Health metrics and cardio data
├── ML_ALGORITHMS.py              # Contains various ML algorithms
├── NN.h5                         # Neural Network model file
├── symptoms_list.py              # Script for managing health symptoms
├── Testing.csv                   # Testing dataset
├── Training.csv                  # Training dataset
├── TRAINING.py                   # Script for training the ML models

# Installation
1. Clone the Repository
git clone https://github.com/your-username/your-repository.git

2. Install required dependencies:
pip install -r requirements.txt

3. Run the backedn:
python3 dm.py

4. Open the frontend in a browser to interact with the enhanced skincare and cardio plan interface.

 # Datasets
The project uses multiple datasets, including:

Health_Doctor_excercise_diet.csv: Contains health metrics and diet-related information.
dataset.csv: General dataset used for the machine learning models.
Training.csv and Testing.csv: Used to train and test the machine learning algorithms.


# Models
# CNN Model
The Convolutional Neural Network (CNN) model (CNN_TESTING.py) is designed for classifying and predicting various health metrics based on the provided dataset.

# Neural Network
A custom neural network model (NN.h5) is integrated into the project for more advanced health predictions, leveraging the training and testing datasets.

# Usage
1. Upload a dataset or use the pre-existing ones for training.

2. Run the training script:
  python3 TRAINING.py

3. After training, run the testing script to evaluate the models:
   python3 CNN_TESTING.py

4. Use the web application to interact with the results and visualize the data.

