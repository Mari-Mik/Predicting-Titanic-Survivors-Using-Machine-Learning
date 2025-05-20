# 🚢 Predicting-Titanic-Survivors-Using-Machine-Learning

This project predicts whether a passenger survived the Titanic disaster using supervised learning. It walks through a full data science pipeline—from raw data exploration to model evaluation—making it an excellent showcase for classification and feature engineering skills.

---

## 📌 Project Highlights

- ✅ Cleaned and processed the Titanic dataset from Kaggle
- 📊 Performed univariate, bivariate, and multivariate analysis
- 🧠 Engineered features like Age Group and Family Size
- ⚖️ Handled class imbalance using **SMOTE**
- 🤖 Trained and compared three models:
  - Tuned **Logistic Regression**
  - **Random Forest**
  - **XGBoost**

---

## 📈 Model Performance

| Model               | Accuracy | Recall (1) | Precision (1) | F1 Score (1) |
|--------------------|----------|------------|----------------|--------------|
| Logistic Regression| 79.39%   | **84%**     | 68.85%         | 75.68%       |
| Random Forest      | 76.72%   | 72%         | 68.57%         | 70.24%       |
| XGBoost            | **82.44%** | 78%      | **76.47%**     | **77.23%**   |

📌 **Conclusion:** XGBoost gave the most balanced and accurate results, while Logistic Regression achieved the best recall, important when predicting survivors.

---

## 🛠 Tools Used

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, SMOTE (imblearn)
- Google Colab, GitHub

---

## 📁 Project Structure
titanic-survival-prediction/
│
├── Predicting Titanic Survivors Using Machine Learning .ipynb # Full analysis and modeling in Google Colab
├── README.md # Project overview and summary

## 🚀 Launch Instruction
To run this project, follow these steps:

1. **Download the Files**
   
   - Download the **`Predicting Titanic Survivors Using Machine Learning .ipynb`** Jupyter notebook and the **`titanic3.xls`** dataset files from the repository.
   - Ensure both files are in the same directory, or update the path to the dataset in the notebook.
   - 
3. **Set Up Your Environment**
   
    Before running the notebook, you need to set up your environment with the required dependencies. You can do this by creating a virtual environment and     
    installing the necessary libraries.

   - Create a virtual environment (optional but recommended):
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
     ```
   - Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     
4. **Change the Dataset Path (If Necessary)**
   
      - If your dataset (`titanic3.xls`) is located in a different directory, update the file path in the notebook:
     ```python
     df = pd.read_csv('path/to/titanic3.xls')
     ```
   - If both files are in the same directory, you don’t need to change anything.

5. **Run the Jupyter Notebook**
   
   - Open a terminal and navigate to the project directory.
   - Launch the Jupyter notebook:
     ```bash
     jupyter notebook Predicting Titanic Survivors Using Machine Learning .ipynb
     ```
   - This will open the notebook in your default browser, and you can start running the code cells.
   - 
6. **Explore the Results**
   
   - After running the cells, you'll see data analysis, feature engineering steps, model training, and performance evaluation.
   - You can interact with the results and experiment with hyperparameters or additional features to improve the model performance.



## 🙋‍♂️ About Me

I'm an aspiring data analyst/data scientist with a passion for solving real-world problems using data.  
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/marimikirtumashvili/) or check out my other projects on [GitHub](https://github.com/Mari-Mik?tab=repositories).
