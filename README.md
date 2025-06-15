# Heart Disease Prediction

A machine learning project that predicts the likelihood of heart disease based on patient health data using Logistic Regression.

## Project Overview

This project implements a heart disease prediction system using machine learning techniques. It analyzes patient health metrics to determine whether a person is likely to have heart disease or not. The model achieves approximately 85% accuracy on training data and 82% accuracy on test data.

## Dataset

The dataset (`heart_disease_data.csv`) contains 303 patient records with 14 attributes:

- **age**: Age in years
- **sex**: Sex (1 = male, 0 = female)
- **cp**: Chest pain type (0-3)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (0-2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (0-2)
- **ca**: Number of major vessels colored by fluoroscopy (0-4)
- **thal**: Thalassemia (0-3)
- **target**: Heart disease diagnosis (1 = disease, 0 = no disease)

## Technology Stack

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Scikit-learn**: Machine learning algorithms and evaluation metrics
- **Google Colab**: Development environment

## Implementation Details

The project follows these key steps:

1. **Data Collection and Processing**: Loading and exploring the dataset
2. **Data Analysis**: Statistical analysis and visualization of the data
3. **Feature Engineering**: Separating features and target variables
4. **Model Training**: Using Logistic Regression algorithm
5. **Model Evaluation**: Assessing model performance with accuracy metrics
6. **Prediction System**: Building a system to predict heart disease for new patient data

## Model Performance

- **Training Data Accuracy**: 85.12%
- **Test Data Accuracy**: 81.97%

## How to Use

1. Clone the repository
2. Ensure you have the required libraries installed:
   ```
   pip install numpy pandas scikit-learn
   ```
3. Run the Python script or open the notebook in Google Colab
4. To make predictions for new patients, use the prediction system with patient data in the required format

## Files in the Repository

- `heart_disease_data.csv`: Dataset with patient records
- `Google Colab Prj Files/prjHeart (1).ipynb`: Jupyter notebook with complete code and analysis
- `Google Colab Prj Files/prjheart.py`: Python script version of the project
- `ML Project report.pdf`: Detailed project report
- `Heart Disease Prediction.pptx`: Presentation slides
- `Demo.mp4`: Video demonstration

## Future Improvements

- Implement additional machine learning algorithms for comparison
- Feature selection to identify most important predictors
- Hyperparameter tuning to improve model performance
- Develop a web interface for easy user interaction

## Contributors

This project was developed as part of a machine learning course project.

## License

This project is available for educational and research purposes. 