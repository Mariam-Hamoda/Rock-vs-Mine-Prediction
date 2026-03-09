# Rock vs. Mine Prediction

### Project Overview
This project is a Machine Learning binary classifier designed to distinguish between **Rocks** and **Naval Mines** using sonar data. It serves as a practical application of signal processing and binary classification in underwater environments.

---

### Technical Stack
* **Language:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy
* **Model:** Logistic Regression (Binary Classification)

---

### Dataset Information
The dataset consists of sonar signal data with **60 frequency attributes** bounced off either a metal cylinder (Mine) or a rock.

* **Target Labels:** 
  * **M (Mine):** Encoded as 0
  * **R (Rock):** Encoded as 1

---

### Implementation Steps

1. **Data Preprocessing:** Loading and analyzing the sonar dataset using Pandas to ensure data integrity.
2. **Label Encoding:** Converting categorical labels (M and R) into numerical values (0 and 1) for model compatibility.
3. **Train-Test Split:** Dividing the dataset into training and testing sets to evaluate the model on unseen data.
4. **Model Training:** Implementing the **Logistic Regression** algorithm to identify patterns within the sonar frequencies.
5. **Model Evaluation:** 
   * Training Accuracy: Approximately **83%**
   * Test Accuracy: Approximately **78%**
6. **Predictive System:** Developing a custom function to process raw sonar data and generate a clear classification output.

---

### Conclusion
The model demonstrates a stable performance with a small margin between training and testing accuracy, indicating a well-fitted model that generalizes well to new data.
