# Curepolygon: Personalized Medical Recommendation System

Curepolygon is a sophisticated Personalized Medical Recommendation System designed to assist users in managing their health effectively. Leveraging advanced machine learning techniques, the system accurately predicts potential diseases based on user-input symptoms.

## Dataset and Tools

The system utilizes a dataset loaded from `Training.csv` for training and testing. Initial data exploration and preprocessing steps are performed using pandas.

## Training Models

Several machine learning models are trained to predict diseases:
- Support Vector Machine (SVC)
- Random Forest Classifier
- Gradient Boosting Classifier
- K Nearest Neighbors Classifier
- Multinomial Naive Bayes

The models are evaluated based on accuracy scores and confusion matrices to determine their effectiveness in disease prediction. The Support Vector Machine (SVC) model, with an impressive accuracy of **99.26%**, is selected for deployment using Flask. This ensures that the trained model is accessible through a web interface, facilitating real-time disease prediction for users.

## Recommendation System and Prediction

The system incorporates additional datasets (`symtoms_df.csv`, `precautions_df.csv`, `workout_df.csv`, `description.csv`, `medications.csv`, `diets.csv`) to provide comprehensive recommendations and predictions:
- **Description:** Provides detailed descriptions of predicted diseases.
- **Precautions:** Lists preventive measures for each disease.
- **Medications:** Suggests appropriate medications.
- **Diets:** Recommends suitable diet plans.
- **Workout:** Suggests workout routines beneficial for specific conditions.

## Deployed Model Demo
![CurePolygon](https://github.com/Aryansh-kr/Hangman_Game/assets/127012188/0e387764-d332-4253-94a2-7fcfb874a953)


## Usage

1. **Input Symptoms:** Users input their symptoms (comma-separated).
2. **Receive Predictions:** The system predicts the disease based on symptoms.
3. **Get Recommendations:** Detailed recommendations including description, precautions, medications, diets, and workouts are provided.

## Future Scope

- **Enhanced User Interface:** Improve the user experience with a more intuitive and interactive interface.
- **Integration with Wearable Devices:** Incorporate data from wearable health devices to enhance predictive accuracy and personalization.
- **Continuous Model Improvement:** Implement mechanisms to continuously update and improve the disease prediction models based on real-time user feedback and new research data.
- **Expand Disease Coverage:** Include more diseases and conditions in the prediction and recommendation system to cater to a wider range of health concerns.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Flask

