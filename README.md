🧠 Multiple Disease Diagnosis System
Predict Pneumonia, Diabetes, and Heart Disease using machine learning and deep learning models. Built with Streamlit, trained using Kaggle datasets.

🚀 Tech Stack
Tool/Tech	Purpose
Python	Backend language
Streamlit	Web UI Framework
Scikit-learn	ML Models (Diabetes, Heart)
TensorFlow/Keras	CNN Model (Pneumonia)
Kaggle Datasets	Medical training data
Matplotlib, Seaborn	Visualization & Charts

📁 Datasets Used (Kaggle)
Pneumonia Detection
Dataset: Chest X-Ray Images (Pneumonia)
Structure:


Diabetes
Dataset: Pima Indians Diabetes Database

Heart Disease
Dataset: Heart Disease UCI Dataset

📦 Project Setup

git clone https://github.com/im-sona/Multiple-disease-diagnosis-system.git
cd Multiple-disease-diagnosis-system
pip install -r requirements.txt
streamlit run app.py

🔍 Pneumonia Prediction
To predict pneumonia, users are prompted to upload a chest X-ray image. The model — typically a Convolutional Neural Network (CNN) — analyzes the uploaded image to detect visual indicators of pneumonia, such as:

Lung opacity

Inflammation

Structural abnormalities in the lungs

📸 Sample Input:
<img width="900" height="506" alt="a3312043-d65f-4af6-91c2-25dda0c88794" src="https://github.com/user-attachments/assets/a1b6b0b6-2e46-43dd-95aa-91d458b43d39" />
 



🧠 Prediction Output:

<img width="895" height="463" alt="4da4d16a-9411-4223-b7ae-f0101137a319" src="https://github.com/user-attachments/assets/b89cc429-d511-4240-a824-6ee01882351e" />

The system displays the diagnosis outcome, identifying whether pneumonia is present based on the analysis.



✅ Example of Normal Chest X-ray (No Pneumonia):

This image shows a clear lung with no opacities, indicating a healthy respiratory system.

<img width="908" height="394" alt="fe66db9e-8c2f-4157-9ca7-2c74c2579b72" src="https://github.com/user-attachments/assets/2091e6fd-892e-4f45-a2ec-364943aca6c3" />


💉 Diabetes Prediction
Users input numerical health values into the interface, including:

Age

Blood glucose level

Blood pressure

Insulin level

BMI (Body Mass Index)

The model (e.g., logistic regression or neural network) processes these features and returns a prediction on the likelihood of diabetes.

🧾 User Input Interface:
<img width="905" height="509" alt="839da24d-2a2a-40f5-af8c-7ef866f12b89" src="https://github.com/user-attachments/assets/363452dd-044f-4038-a4ea-2513e2f01645" />



📊 Prediction Output:
<img width="973" height="408" alt="6b39cb66-b856-4258-9b3e-3ea8ffa0840a" src="https://github.com/user-attachments/assets/925947a3-ce13-4d8c-9627-babd3d0e3d58" />


The system predicts whether the user is diabetic and may show probability or risk classification.



❤️ Heart Disease Prediction
Users provide key medical data including:

Age

Resting blood pressure

Cholesterol levels

Maximum heart rate

ST depression (ECG analysis)

A machine learning model analyzes these inputs to determine the presence or absence of heart disease.

🩺 Result Display:

<img width="981" height="522" alt="676f4538-9fc0-4341-837d-2c2460c207f4" src="https://github.com/user-attachments/assets/f235c8df-128d-47a8-962d-b24cbc972165" />


The system returns an accurate and interpretable prediction to help users and clinicians understand heart disease risk.

✨ Features of the UI
✅ Simple and clean layout

✅ Real-time disease predictions

✅ Visual and numerical input support

✅ Responsive and user-friendly design

✅ Seamless interaction with ML models
