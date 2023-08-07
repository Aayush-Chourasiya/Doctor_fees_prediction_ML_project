 # Doctor Fee Prediction

The project's goal is to build a web interface where users can predict the consultation fees of doctors by entering their information. The machine learning model used in this interface was trained on data collected from the Practo website using Selenium. The scraped data was then carefully processed and organized using Python Pandas to ensure accurate predictions.
![Screenshot (1631)](https://github.com/Aayush-Chourasiya/Doctor_fees_prediction_ML_project/assets/133970565/1308edd1-768b-4bcf-83ff-dc20b85c0901)

![image](https://github.com/Aayush-Chourasiya/Doctor_fees_prediction_ML_project/assets/133970565/58b0fa4a-e60d-41ff-8ed7-0b09c8934b05)




# Findings from the Doctor Fee Prediction Project 🧪
According to the Practo dataset, Bangalore has the highest number of doctors.

The most common degrees among doctors are MBBS, MD, and BDS, with the highest representation in the dataset.

The dataset indicates that the three most prominent specialties among doctors are:

Dentist
Gynecologist
Pediatrician

# 🏥 Doctor Fee Prediction ML Model Creation Steps 🧠

1. Data Collection: Gathered doctor-related information from Practo using web scraping techniques with Selenium.

2. Data Preprocessing: Conducted thorough data cleaning, handling missing values, and transforming categorical variables into numerical representations.

3. Feature Engineering: Derived additional relevant features from the existing dataset, such as extracting qualifications.

4. Model Selection: Explored various regression algorithms and selected potential candidates based on initial performance evaluation.

5. Hyperparameter Tuning: Utilized GridSearchCV to fine-tune hyperparameters for each selected model, optimizing their performance.

6. Model Training: Trained multiple models on the dataset with tuned hyperparameters to improve predictive accuracy.

7. Weighted Voting: Implemented a Weighted Voting technique, combining predictions from multiple models, each with a specific weight.

8. Model Evaluation: Evaluated the ensemble model using appropriate metrics such as Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE) to measure prediction accuracy.

9. Web App Development: Developed a user-friendly web application using Flask, HTML, and CSS to offer an intuitive interface for users to input parameters.

# 🏥 Doctor Fee Prediction Web application

![Screenshot (1634)](https://github.com/Aayush-Chourasiya/Doctor_fees_prediction_ML_project/assets/133970565/7c3755e5-635f-4c96-8558-e5072dd32a98)
