# AI-Health-Insurance-Prediction🏥
📌 Project Overview

AI Health Insurance Prediction is a Machine Learning project developed using Azure Machine Learning Studio to predict health insurance charges based on user details such as age, BMI, smoking habits, and region.

The goal of this project is to automate insurance cost estimation, helping companies and individuals make faster and more accurate decisions.

🎯 Problem Statement

Insurance companies traditionally calculate premiums manually or using basic rules. This process:

Takes time

Can be inconsistent

Lacks predictive intelligence

This project solves the problem by:

Using Machine Learning to predict insurance charges

Providing fast and data-driven results

Reducing manual effort

🚀 Solution Approach

The solution is built using end-to-end ML workflow in Azure Machine Learning Studio:

Data Collection

Data Preprocessing

Feature Engineering

Model Training

Model Evaluation

Model Deployment

🧠 Machine Learning Model

Regression-based model used for prediction

Trained on health insurance dataset

Evaluated using standard metrics like:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

☁️ Azure Implementation

This project is fully developed on **Microsoft Azure platform:

✔️ Services Used

Azure Machine Learning Studio – Model development & training

Azure Blob Storage – Dataset storage

Azure Container Instances – Model deployment

⚙️ Model Deployment

The trained model is deployed as a real-time endpoint

Deployment is done using Azure Container Instances

Users can send input data and get predictions via API

📊 Features

Predicts insurance charges instantly

Cloud-based scalable solution

End-to-end ML pipeline

Easy API integration

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

Azure Machine Learning Studio

REST API

📂 Project Workflow
Data → Preprocessing → Training → Evaluation → Deployment → Prediction API
🔌 API Usage (Example)
POST /predict

{
  "age": 25,
  "bmi": 28.5,
  "children": 1,
  "smoker": "no",
  "region": "northwest"
}

Response:

{
  "predicted_insurance_cost": 3200
}
⚠️ Challenges Faced

Resource provider errors during deployment

Limited free-tier resources on Azure

Region-based deployment restrictions

✅ Conclusion

This project demonstrates how Machine Learning + Cloud (Azure) can be used to:

Automate insurance prediction

Improve accuracy

Build scalable AI solutions

🔮 Future Improvements

Add frontend dashboard

Improve model accuracy using advanced algorithms

Deploy using serverless endpoints

Integrate with real-world insurance systems

👨‍💻 Author

Naitik Ganvir
