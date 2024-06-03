# Virtual-Health-Care
 # 🏥 Medicine Recommender System

An AI-driven web application that provides personalized medical insights based on user-input symptoms. This project demonstrates the power of machine learning in making healthcare more accessible.

## 🚀 Features

- **Smart Symptom Input**: Enter symptoms in natural language (e.g., "itching, joint pain, fatigue").
- **AI-Powered Diagnosis**: Utilizes a trained SVM classifier to predict possible conditions.
- **Fuzzy Text Matching**: Understands misspellings or synonyms using FuzzyWuzzy.
- **Holistic Recommendations**:
  - Disease description
  - Precautionary measures
  - Medication suggestions
  - Tailored diet plans
  - Suitable workout routines

## 🛠 Tech Stack

- **Backend**: Flask
- **Machine Learning**: Scikit-learn (SVM classifier)
- **Data Handling**: Pandas, NumPy
- **Text Processing**: FuzzyWuzzy
- **Frontend**: HTML, CSS 

## 🚦 Prerequisites

- Python 3.7+
- pip

## 🚀 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/medicine-recommender-system.git
cd medicine-recommender-system

# Set up a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt


 
