# 🌱 Optimizing Organic Waste to Fertilizer Conversion Using Machine Learning

This project leverages advanced machine learning techniques to predict fertilizer quality based on key soil and processing features. It combines classical regression models, LSTM deep learning, and model stacking to deliver accurate predictions and actionable recommendations for improving soil fertility.

---

## 📌 Features

- 📊 **Data Preprocessing** with normalization and missing value handling
- 🧠 **Model Stacking** combining KNN, Linear Regression, Random Forest, and Gradient Boosting
- 🤖 **LSTM-based Prediction Model** for capturing sequential patterns in data
- 📈 **Final Ensemble Model** blending predictions from stacked and LSTM models
- 📋 **Interactive Report Generator** that takes user input and offers improvement suggestions

---

## 🚀 Technologies Used

| Category        | Tools & Libraries                                |
|-----------------|--------------------------------------------------|
| Machine Learning| `scikit-learn` (Stacking, RandomForest, KNN, etc.)|
| Deep Learning   | `TensorFlow`, `Keras` (LSTM model)               |
| Data Processing | `pandas`, `numpy`, `StandardScaler`              |
| Evaluation      | `mean_squared_error`, `r2_score`                 |
| Model Saving    | `joblib`, `.h5` (Keras model)                    |

---

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ommishra03/Optimizing-Organic-Waste-to-Fertilizer-Conversion-Using-Machine-Learning.git
   cd Optimizing-Organic-Waste-to-Fertilizer-Conversion-Using-Machine-Learning```

2. **Install dependencies**

   ```bash
   pip install pandas numpy scikit-learn tensorflow joblib
   ```
3. **Run the script**

   ```bash
   python your_script_name.py
   ```

> 📂 Make sure the file `encoded_fertilizer_dataset.csv` is placed in the appropriate directory.

---

## 📥 Input

* Soil and process features including:

  * Moisture Content
  * pH Level
  * Carbon, Nitrogen, Phosphorus, Potassium Content
  * Microbial Activity
  * Processing Time & Temperature
  * Energy Consumption

---

## 📤 Output

* ✅ Predicted Fertilizer Quality Score
* 📈 Fertility recommendations (based on threshold values for key nutrients)
* 🧠 Model evaluation: RMSE and R²
* 💾 Trained models saved as `stacking_regressor.pkl` and `lstm_model.h5`

---

## 📚 About the Author

👨‍🎓 **Om Mishra**
📍 Third-year Student, Chandigarh University
🏆 Reliance Foundation Scholar
🧠 Mentor at Reliance Foundation (C, C++, DSA, Python)
🌐 Blockchain & AI Enthusiast (Solidity, Ethereum, React, ML)
🎮 Hackathon Finalist (NASA Space App Challenge, NITs, BITS)
📢 Rebuilt math curriculum at an ed-tech startup
🧑‍🏫 Taught merchant navy aspirants

🔗 [Connect on LinkedIn](https://www.linkedin.com/in/om-mishra-a62991289)

---

## ✨ Acknowledgements

* 🧠 `scikit-learn` for classical ML models and stacking
* 🤖 `TensorFlow` & `Keras` for LSTM implementation
* 📊 `StandardScaler` for data normalization
* 📄 `joblib` for model serialization

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 📧 Contact

For feedback or collaboration: **[ommishra1729@gmail.com](mailto:ommishra1729@gmail.com)**


---

Let me know if you'd like a `requirements.txt` or want this adapted into a Streamlit or Flask app interface next!
```
