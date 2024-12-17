# Algerian Forest Fires Prediction

This project focuses on predicting the likelihood of forest fires in Algeria using weather and environmental data. It employs machine learning models such as Ridge Regression to analyze data and predict fire outbreaks based on factors like temperature, humidity, wind speed, and more. The application provides real-time predictions for fire risk, helping in forest management and safety.

---

## **Project Overview**

The Algerian Forest Fires project uses a cleaned dataset with features like temperature, humidity, wind speed, and fire weather index (FWI) to train a predictive model. The project aims to predict fire outbreaks and provide insights into the factors that contribute to these fires, focusing on regions like Bejaia and Sidi-Bel Abbes.

---

## **Repository Contents**

- **Notebooks**:
  - `EDA and FE.ipynb`: Exploratory Data Analysis and Feature Engineering
  - `Model Training.ipynb`: Model training and evaluation
- **Dataset**:
  - `Algerian_forest_fires_cleaned_dataset.csv`: Cleaned dataset with features like temperature, humidity, wind speed, etc.
  - `Algerian_forest_fires_dataset_UPDATE.csv`: Updated dataset with region-specific data (Bejaia and Sidi-Bel Abbes).
- **Models**:
  - `ridge.pkl`: Trained Ridge Regression model for fire prediction.
  - `scaler.pkl`: Scaler used to preprocess the data for model predictions.
- **Templates**:
  - `home.html`: Main page of the web application.
  - `index.html`: The index page of the web application.
- **Application**:
  - `application.py`: Flask application for deploying the model.
- **requirements.txt**: Dependencies needed to run the project.
- **LICENSE**: MIT License for project use.

---

## **Technologies Used**

- **Programming Language**: Python
- **Libraries**: 
  - Data Analysis: `Pandas`, `NumPy`
  - Machine Learning: `Scikit-learn`, `Ridge Regression`
  - Data Visualization: `Matplotlib`, `Seaborn`
  - Web Framework: `Flask`

---

## **Setup Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Monish-Nallagondalla/Algerian_forest_fires.git
   cd Algerian_forest_fires

2. **Install Dependencies**:
  ```bash
 pip install -r requirements.txt
 ```

3. **Run the Flask Application**:
 ```bash
 python application.py
 ```
4. Open the web application in your browser (localhost:5000).
   
---

## **Key Insights and Results**
Fire Prediction: The model accurately predicts the likelihood of forest fires based on environmental conditions.

Factors Influencing Fires: Temperature, wind speed, and the Fire Weather Index (FWI) are significant factors in fire outbreaks.

Region-Specific Analysis: Different regions exhibit unique fire risks, with Bejaia and Sidi-Bel Abbes showing varying fire patterns.

---

## **Future Work**
Explore other machine learning models (e.g., Random Forest, XGBoost) for better accuracy.

Integrate real-time weather data for dynamic fire risk predictions.

Expand the dataset to include more Algerian regions for comprehensive predictions.

---

## **Acknowledgements**
This project was completed as part of my analysis on forest fire prediction. I would like to thank my mentors and colleagues for their support and insights.

---

## **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

## **Contact**
For inquiries or collaborations, feel free to contact:

Name: Monish Nallagondalla
GitHub: Monish-Nallagondalla
   
