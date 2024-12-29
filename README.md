# AI-Powered Investment Risk Analysis and Recommendations

## 📜 Project Overview
This project focuses on leveraging artificial intelligence to analyze user investment preferences and provide personalized investment recommendations based on their risk profiles. The solution integrates data collection, preprocessing, feature engineering, and advanced machine learning models like XGBoost to deliver reliable and actionable insights for investors.

---

## 🎯 Objectives
1. **Risk Profiling:** Classify users into three distinct risk categories: Low Risk, Medium Risk, and High Risk.
2. **Investment Recommendations:** Provide tailored investment suggestions for each risk category to enhance financial literacy and decision-making.
3. **Data-Driven Insights:** Leverage user behavior and preferences to model and predict optimal investment paths.

---

## 🛠️ Key Features
- **Risk Scoring System:** A weighted scoring mechanism that uses significant features (e.g., RISK_RETURN_MAKUL, RISK_SCORE_BOYS_GIRLS) to calculate a risk score for each user.
- **Investment Suggestions:** Personalized investment options based on risk categories, such as:
  - Low Risk: Deposit accounts, money market funds.
  - Medium Risk: Stable stocks in BIST30, mutual funds.
  - High Risk: Volatile stocks, cryptocurrencies.
- **Machine Learning Model:** Utilizes **XGBoost** for classification, achieving high performance metrics:
  - Accuracy: 82.69%
  - F1 Score: 82.40%
  - ROC-AUC: 83.90%
- **Synthetic Data Balancing:** Uses SMOTE to address data imbalance across risk categories.

---

## 🚀 Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `XGBoost`
  - Imbalanced Data Handling: `imbalanced-learn`
- **AI Model:** XGBoost (Extreme Gradient Boosting)
- **Data Collection Tool:** Google Forms

---

## 📊 Results
- Successfully classified users into three risk categories with high model accuracy and reliability.
- Provided actionable investment suggestions tailored to user profiles.
- Enhanced understanding of factors influencing investment decisions through feature importance analysis.

---

## 📂 Project Structure
```plaintext
├── data
│   ├── Yatirimci_Anketi.csv         # Dataset collected via Google Forms
├── src
│   ├── data_preprocessing.py        # Data cleaning and feature engineering scripts
│   ├── risk_scoring.py              # Risk scoring and classification logic
│   ├── model_training.py            # Model training and evaluation
├── notebooks
│   ├── YapayZekaSunum.ipynb         # Presentation and visualizations
├── README.md
```

---

## 🔍 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-investment-risk-analysis.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script for data preprocessing and model training:
   ```bash
   python src/main.py
   ```
4. Explore the results and visualizations in the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/YapayZekaSunum.ipynb
   ```

---

## 📖 Learn More
- **Project Motivation:** This project addresses the need for informed financial decision-making by providing users with actionable investment strategies tailored to their risk tolerance.
- **Future Enhancements:**
  - Expand the dataset for more robust predictions.
  - Integrate a web interface for real-time user interaction.
  - Add NLP-based feedback analysis to refine recommendations.

---

## 🤝 Acknowledgements
Special thanks to **Melih Ağraz** for guidance and support throughout this project. This work was completed as part of the "Yapay Zeka" course at [Your Institution].

---

## 📬 Contact
- **Author:** Çağrı Tuğrul Keser
- **Email:** [Cagritugrulkeser@gmail.com](mailto:Cagritugrulkeser@gmail.com)
- **LinkedIn:** [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile/)

Feel free to explore the repository and provide feedback!
