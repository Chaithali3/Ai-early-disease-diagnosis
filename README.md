# Ai-early-disease-diagnosis
Empowering healthcare for all with faster predictions,reduced,and accessible cloud-based diagnosttics

## Problem
Many patients in India are diagnosed late, increasing treatment cost and reducing survival — especially in rural and semi-urban areas with few specialists.

## Solution
An accessible web app that collects simple health inputs, calls an AI model (deployed on Azure ML) to predict disease risk (e.g., diabetes), shows results and recommendations, and stores anonymized records in Azure SQL.

## Architecture 
User (Web) → Azure App Service (Frontend) → Azure Functions (Backend) → Azure ML (Prediction)
Azure ML → Azure SQL (Storage)
Results Dashboard → Azure Logic Apps (Notifications)

## Tech stack
- Frontend: React.js (hosted on Azure App Service)
- Backend: Python (Azure Functions)
- AI/ML: Azure Machine Learning + scikit-learn
- Database: Azure SQL
- Cloud: Microsoft Azure(App Service,Functions,ML)
- Notifications: Azure Logic Apps (optional)
