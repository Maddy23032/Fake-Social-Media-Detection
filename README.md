# Fake Social Media Detection

This project is designed to detect fake social media accounts using machine learning models, specifically Random Forest and Decision Tree classifiers. The application provides a web interface for users to input account data and receive predictions on whether an account is likely to be fake or genuine.

## Features
- **Machine Learning Models:** Utilizes Random Forest and Decision Tree models for classification.
- **Web Interface:** User-friendly web app built with Flask for easy interaction.
- **Data Visualization:** Displays results and model predictions in a clear format.
- **Pre-trained Models:** Includes pre-trained model files for immediate use.

## Project Structure
```
CODE/
├── app.py                  # Main Flask application
├── data.csv                # Dataset used for training/testing
├── Decision_tree.sav       # Saved Decision Tree model
├── Logistic_Regression.sav # (Optional) Logistic Regression model
├── Random_forest.sav       # Saved Random Forest model
├── fake_account.ipynb      # Jupyter notebook for data analysis/modeling
├── fake.html               # HTML template for fake account prediction
├── static/                 # Static files (CSS, JS, images)
│   ├── css/
│   ├── images/
│   └── js/
└── templates/              # HTML templates for the web app
    ├── about.html
    ├── contact.html
    ├── index.html
    ├── model.html
    ├── prediction.html
    ├── service.html
    └── view.html
```

## Getting Started

### Prerequisites
- Python 3.x
- Required Python packages (see below)

### Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd "Fake Social media detection/CODE"
   ```
3. Install dependencies:
   ```sh
   pip install flask scikit-learn pandas numpy
   ```

### Running the Application
1. Start the Flask app:
   ```sh
   python app.py
   ```
2. Open your browser and go to `http://127.0.0.1:5000/` to use the web interface.

## Usage
- Upload or input social media account data via the web interface.
- The app will use the pre-trained Random Forest and Decision Tree models to predict if the account is fake.
- View results and model details on the web pages.

## Files
- `app.py`: Main application logic and routing.
- `data.csv`: Dataset for model training/testing.
- `Decision_tree.sav`, `Random_forest.sav`: Pre-trained model files.
- `fake_account.ipynb`: Notebook for data exploration and model building.
- `templates/`: HTML templates for the web interface.
- `static/`: CSS, JS, and image assets.

## License
This project is for educational purposes.

## Acknowledgements
- Developed using Flask and scikit-learn.
- Inspired by the need to detect fake accounts on social media platforms.