# Fish Species Prediction Web App

This is a Flask-based web application that predicts the species of a fish based on its various features. The app uses a trained machine learning model to make accurate predictions. Simply input the fish's measurements, and the app will display the predicted species.

# Demo
To see a live demo of the web app, visit http://susmitha0226.pythonanywhere.com/

## Getting Started
### Prerequisites
- Python 3.x (3.6 or higher recommended)
- Flask
- scikit-learn
- pandas
- joblib

### Installation

1. Clone the repository:

```
git clone https://github.com/Su5mitha/Lab4_Fish_Market_Dataset.git
```
#### Change directory
```
cd Lab4_Fish_Market_Dataset
```

2. Install the required dependencies:

```
pip install requirement.txt
```

## Usage

1. Run the Flask application:

```
python app.py
```


2. Access the application in your web browser at `http://localhost:5000/`.

3. Fill in the features for the fish in the provided form and click "Predict" to get the predicted species.

## Model Training
The machine learning model used in this web app is a Random Forest classifier. It has been trained on the Fish Market dataset, which contains various fish species along with their features.

The training code and data preprocessing can be found in the ml.ipynb Jupyter Notebook.

# File Structure
- app.py: Flask web app main script.
- templates/: Folder containing HTML templates for the web app.
- trained_model.pkl: Serialized trained Random Forest classifier.
- fish_market_dataset.csv: Fish Market dataset used for training the model.
- requirements.txt: List of required Python libraries and their versions.
