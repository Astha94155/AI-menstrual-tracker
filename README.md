# AI menstrual tracker


 AI-Based Menstrual Cycle & PCOS Risk Tracker

 Project Overview

This project is an AI-based application designed to track menstrual cycles and assess potential PCOS (Polycystic Ovary Syndrome) risk. Unlike traditional trackers that rely on simple averages, this system uses machine learning to provide intelligent predictions and insights based on user data.

---

Objectives

* Predict the next menstrual cycle using past data
* Analyze symptoms to estimate PCOS risk
* Provide visual insights through graphs
* Demonstrate the application of AI in healthcare

---

 Features

*  Input and track menstrual cycle lengths
*  Cycle prediction using **Linear Regression**
*  PCOS risk classification using **Decision Tree**
*  Graphical visualization of cycle trends
*  Basic health suggestions based on results

---

 Technologies Used

* Python
* Streamlit (UI)
* NumPy
* Scikit-learn
* Matplotlib

---

 How It Works

1. User enters past cycle lengths
2. User provides symptom scores (acne, weight gain, mood swings)
3. The system:

   * Predicts next cycle using Linear Regression
   * Calculates variation in cycle length
   * Classifies PCOS risk using Decision Tree
4. Displays results along with graph and suggestions

---

 Installation & Setup

 Clone the repository

```bash
git clone https://github.com/Astha94155/menstrual-ai-tracker.git
cd menstrual-ai-tracker
```

  Install dependencies

```bash
pip install -r requirements.txt
```

 


 Sample Output

* Predicted next cycle length (in days)
* PCOS risk level: Low / Medium / High
* Graph showing cycle history
* Health suggestions



 Limitations

* Uses a small/dummy dataset
* Not a medical diagnostic tool
* Accuracy can be improved with real-world data



 Future Scope

* Integration with real medical datasets
* Advanced ML models for better prediction
* Mobile application development
* Personalized health recommendations



 Author

Astha Singh

