# Student Exam Performance Predictor

This project aims to predict student exam scores based on various input features such as gender, ethnicity, parental education level, lunch type, and scores in reading and writing. The model provides insights into how these factors influence student performance.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Input Features](#input-features)
- [Model Training](#model-training)
- [Predictions](#predictions)
- [License](#license)

## Installation

To run this project, ensure you have Python 3.x installed. Follow these steps to set up the environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-exam-performance-predictor.git
   cd student-exam-performance-predictor
2. Create and activate a virtual environment (optional but recommended):
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate` 

3. Install the required packages:
   pip install -r requirements.txt

 ##  Usage
 
 To start the web application, run the following command:
 python application.py

 Open your web browser and navigate to http://localhost:8080/predictdata to access the application.

 ## Input Features

 The model uses the following input features:

	•	Gender: Gender of the student (e.g., Male, Female).
	•	Race or Ethnicity: Categorized race/ethnicity groups (e.g., Group A, Group B, etc.).
	•	Parental Level of Education: Highest level of education attained by the student’s parents (e.g., High school, Bachelor’s degree).
	•	Lunch Type: Type of lunch received by the student (e.g., Free/reduced, Standard).
	•	Test Preparation Course: Completion status of a test preparation course (e.g., None, Completed).
	•	Reading Score: Score obtained in reading (out of 100).
	•	Writing Score: Score obtained in writing (out of 100).

## Model Training

The model is trained using historical data that correlates these features with students’ final exam scores. The model’s performance can be evaluated using metrics such as r2_score. 


## Predictions

After inputting the required information in the web application, the model predicts the student’s expected math score based on the provided features. The results will be displayed on the same page.


## License

This project is licensed under the MIT License. See the LICENSE file for more details.