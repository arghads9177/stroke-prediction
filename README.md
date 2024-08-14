# Stroke Prediction Model

## Context

According to the World Health Organization (WHO), stroke is the second leading cause of death globally, responsible for approximately 11% of total deaths. This project uses a dataset to predict whether a patient is likely to suffer a stroke based on input parameters such as gender, age, various diseases, and smoking status. Each row in the dataset provides relevant information about a patient.

## Dataset

The dataset contains the following attributes:

- **id**: Unique identifier
- **gender**: "Male", "Female", or "Other"
- **age**: Age of the patient
- **hypertension**: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- **heart_disease**: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- **ever_married**: "No" or "Yes"
- **work_type**: "children", "Govt_job", "Never_worked", "Private", or "Self-employed"
- **Residence_type**: "Rural" or "Urban"
- **avg_glucose_level**: Average glucose level in blood
- **smoking_status**: "formerly smoked", "never smoked", "smokes", or "Unknown"*
- **stroke**: 1 if the patient had a stroke, 0 if not

*Note: "Unknown" in `smoking_status` means that the information is unavailable for this patient.

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for analysis and model training
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, feature engineering, feature selection, and model development, evaluation & optimization.
- `models/`: Saved models and evaluation results
- `README.md`: Project overview and documentation

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/stroke-prediction.git

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact **Argha Dey Sarkar** at **email2argha@gamil.com**.
