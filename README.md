
# Tele Healthcare App (Phase 1)

This project aims to develop a healthcare prediction application designed to assist users in assessing their potential risk for heart disease and diabetes. This initial phase focuses on data collection, processing, and deployment of AI/ML models for predictions. The application will eventually offer two dedicated pages for these specific conditions.


## Current Features

- Data Collection:
Integrated data collection pipelines for heart disease and diabetes risk factors.
Sources include medical records, wearable devices, and user-submitted data.
- Data Processing:
Standardized and pre-processed data for compatibility with AI/ML models.
Performed data cleaning and feature engineering to enhance model performance.
- AI/ML Model Deployment:
Trained and deployed AI/ML models for heart disease and diabetes prediction.
Utilized various machine learning techniques, including logistic regression and random forests.
Optimized model parameters for accurate and reliable predictions.

## Phase 1 Deliverables

- Functional application with data collection and processing capabilities.
 - Deployed AI/ML models for heart disease and diabetes prediction.
 - Initial user interface prototypes for both prediction pages.


## Server-side:

**Framework:** Flask (Python)

**Libraries:**
- `pickle` (for loading the model)
- `numpy` (for numerical operations)
- `request` (for handling HTTP requests)
- `send_from_directory` (for serving static files)
- `render_template` (for generating HTML templates)

## Client-side:

**JavaScript Framework:** Vite (for fast development) with ReactJS (for building user interfaces)

**CSS Framework:** Tailwind CSS (for utility-first CSS)

## Other:

**Machine learning model:** A pre-trained model for heart disease prediction saved in the `heartDisease_model.pkl` file. The specific machine learning algorithm used is not specified in the provided code.
## Future Development:

1. **Completion of User Interface:**
   - Incorporate interactive elements and visualizations to enhance user experience.
   - Finalize the application's interface design for intuitive and user-friendly interaction.

2. **Integration of Additional Health Assessments:**
   - Include more health risk assessments and prediction models for a comprehensive health analysis.
   - Expand the application's capability to cover a broader range of health conditions or concerns.

3. **Implementation of Personalized Health Recommendations:**
   - Develop algorithms to generate personalized health recommendations based on individual health data and assessments.
   - Provide tailored interventions or suggestions for improving health outcomes.

4. **Incorporation of User Feedback:**
   - Collect and analyze user feedback to identify areas for improvement and features in demand.
   - Continuously refine and expand the application based on user suggestions and preferences.

## Run Locally

1. **Clone the Repository or Download the Source Code:**
   Download the source code or clone the repository to your local machine.

2. **Install Dependencies:**
   Navigate to the project directory using the terminal or command prompt, then install the required Python packages:
   ```bash
   pip install Flask numpy scikit-learn pandas matplotlib seaborn

3. **Run the Application:**
   - Navigate to the directory containing the Flask application (where the app.py or main Python file is located).
   - Run the Flask application:
     ```bash
     python app.py
     ```
   - You should see output indicating that the Flask server is running, typically on http://127.0.0.1:5000/ or http://localhost:5000/.

4. **Access the Web Application:**
   Open a web browser and enter http://127.0.0.1:5000/ or http://localhost:5000/ in the address bar.

5. **Use the Application:**
   - Enter the medical features as required.
   - Click the "Predict" button.
   - The machine learning model should process the data and display the prediction results on the webpage.



