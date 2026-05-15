# EV Charging Demand Prediction 🚗⚡

## Overview
This project uses Machine Learning techniques to predict Electric Vehicle (EV) charging demand based on historical EV adoption and population datasets. The project focuses on forecasting future charging requirements to support smart energy management and EV infrastructure planning.

---

## Features
- EV demand forecasting using Machine Learning
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Visualization of EV trends
- Predictive model generation
- Model performance evaluation

---

## Tech Stack
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Structure

```bash
EV-Charging-Demand-Prediction/
│
├── data/
│   └── preprocessed_ev_data.csv
│
├── notebooks/
│   └── EV_Adoption_Forecasting.ipynb
│
├── models/
│   └── forecasting_ev_model.pkl
│
├── images/
│   ├── RF_Tree.png
│   └── ev-car-factory.jpg
│
├── app.py
├── requirements.txt
└── README.md
```

---

## Dataset
The dataset contains:
- Electric vehicle population data
- EV adoption trends
- Forecasting-related attributes

Data preprocessing was performed to handle missing values and improve model accuracy.

---

## Machine Learning Workflow
1. Data Collection  
2. Data Cleaning  
3. Feature Engineering  
4. Model Training  
5. Model Evaluation  
6. Prediction & Visualization  

---

## Model Used
- Random Forest Regressor

The model predicts future EV charging demand using historical EV growth patterns.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/EV-Charging-Demand-Prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python app.py
```

---

## Project Preview

### EV Forecast Visualization
![Forecast Graph](RF_Tree.png)

### Electric Vehicle Image
![EV Image](ev-car-factory.jpg)

---

## Future Improvements
- Real-time EV demand prediction
- Streamlit web deployment
- API integration
- Advanced Deep Learning models
- Interactive dashboard

---

## Author
### Ray
BSc IT Student | AI & ML Enthusiast | Web Developer

---

## License
This project is licensed under the MIT License.
