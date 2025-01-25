# Resume-Screening-Application

A Resume Screening System that utilizes Natural Language Processing (NLP) and Machine Learning (ML) techniques to automatically predict candidate profiles from resumes. This application aims to streamline the hiring process by helping recruiters quickly identify suitable candidates based on their resumes.

## Project Overview  
This project focuses on developing an automated resume screening tool that classifies resumes into relevant categories based on the skills, experiences, and qualifications presented in the resume. The system uses NLP and ML algorithms to analyze the content of resumes and predict potential candidate profiles. With an accuracy of 98.5% on training data, this application provides a high level of precision in identifying candidate suitability.

## Features:  
   * High Accuracy: Achieves 98.5% accuracy on training data, leveraging advanced NLP techniques and machine learning models.
   * Data Visualization: Provides insights into resume trends, skill distributions, and candidate profile statistics using Matplotlib and Seaborn.
   * Text Preprocessing and Feature Extraction: Uses TF-IDF vectorization, the sklearn library, and re for data cleaning, preprocessing, and feature extraction.
   * Full-Stack Web Application: Built a user-friendly web interface using Streamlit that allows users to upload resumes and instantly receive predictions.

## Dataset  
The system can be trained on any dataset consisting of labeled resumes with different job categories or roles. For the purposes of this application, a dataset containing resumes along with the relevant job titles, skills, and experience details was used.

## Input:  
* Resumes (in PDF or text format) uploaded by users through the web interface.

## Output:  
* Predicted candidate profile (e.g., job role, experience level, skillset, etc.).

## Technologies and Tools
* Programming Language: Python
* NLP Techniques: TF-IDF vectorization, Tokenization, Lemmatization, Named Entity Recognition (NER)
* Machine Learning Algorithms: Logistic Regression, Support Vector Machine (SVM), Random Forest Classifier
* Libraries:
   * sklearn: For model building, feature extraction, and evaluation
   * matplotlib and seaborn: For data visualization and analysis
   * re: For data cleaning and regular expression-based processing
   * pandas: For data manipulation and analysis
* Web Application Framework: Streamlit (for building the interactive web interface)
* File Upload: Built-in Streamlit functionality for handling file uploads (resumes).

## Installation and Setup
### Prerequisites:
1. Python 3.x
2. Install required libraries by running:  
    pip install -r requirements.txt
### Steps to Run:
1. Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Resume-Screening-Application.git
cd Resume-Screening-Application
Install the necessary dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the web application:

bash
Copy
Edit
streamlit run app.py
The application will be accessible on your local machine at http://localhost:8501.

How it Works
Upload Resume: The user uploads a resume (PDF, text file).
Preprocessing: The resume is preprocessed by cleaning the text, extracting relevant information, and applying NLP techniques like tokenization and lemmatization.
Prediction: The preprocessed data is passed to the trained machine learning model, which predicts the candidate profile based on the extracted features.
Result Display: The system returns the predicted profile, which includes the job role, skills, and experience level that the candidate is suited for.
Data Visualization: In-depth visualizations of resume trends and skill distributions are available for the recruiter’s analysis.
Evaluation Metrics
The model’s performance is evaluated based on:

Accuracy: The percentage of correct predictions made by the model on the test data.
Confusion Matrix: To evaluate the true positive, false positive, true negative, and false negative predictions.
F1-Score: For understanding the balance between precision and recall.
Future Enhancements
Multi-File Upload: Allow batch processing of multiple resumes at once.
Enhanced Model Performance: Incorporate more advanced NLP techniques (e.g., BERT, GPT) for better results.
Job Recommendation System: Develop a feature that suggests suitable job roles based on the candidate’s resume profile.
Contributing
Contributions are welcome! If you’d like to improve this project, feel free to fork the repository, make your changes, and submit a pull request.

Issues:
If you encounter any issues or have suggestions for new features, please feel free to open an issue in the GitHub Issues section.
