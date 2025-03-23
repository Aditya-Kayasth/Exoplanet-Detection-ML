# Hunting Exoplanets in Space using Machine Learning

## 🌌 Project Overview
This project aims to detect exoplanets using data from NASA's **Kepler Space Telescope**. The primary technique employed is the **Transit Method**, which identifies planets by observing periodic dips in a star's brightness as a planet passes in front of it. The project involves **data preprocessing, feature engineering, model training, and evaluation** using machine learning algorithms such as **Random Forest and XGBoost**.

## 📂 Dataset Details
The dataset is derived from NASA's **Kepler Space Telescope**, containing thousands of stellar light curves recorded over time. Each data point represents the brightness level of a star and its variation, which helps in detecting planetary transits.

## 🛠 Installation & Setup
To run this project on your local system:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Hunting-Exoplanets.git
   cd Hunting-Exoplanets
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the provided **Jupyter Notebooks** and follow the execution flow.

## 🔬 Methodology
The project follows these major steps:
1. **Data Preprocessing:** Cleaning and normalizing high-dimensional Kepler data.
2. **Feature Engineering:** Extracting key features from light curve data.
3. **Model Training:** Training classifiers such as **Random Forest and XGBoost**.
4. **Class Imbalance Handling:** Using **SMOTE** to balance positive and negative samples.
5. **Feature Selection:** Implementing **Recursive Feature Elimination (RFE)** for optimal performance.
6. **Evaluation & Optimization:** Using **GridSearchCV** for hyperparameter tuning and **early stopping** for efficiency.

## 🚀 Technologies Used
- **Python** (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow)
- **Machine Learning** (Random Forest, XGBoost, SMOTE, RFE, GridSearchCV)
- **Data Visualization** (Matplotlib, Seaborn)
- **Jupyter Notebook** for interactive analysis

## 📊 Results & Insights
The final trained model achieved **99% accuracy**, effectively detecting exoplanets based on transit light curves. Advanced feature selection and preprocessing significantly improved the predictive capability.

## 📖 How to Use
- **Data Exploration:** Start with `1_Data_Preprocessing.ipynb` to understand the dataset.
- **Feature Engineering & Selection:** Follow `2_Feature_Engineering.ipynb`.
- **Model Training & Evaluation:** Run `3_Model_Training.ipynb`.
- **Final Predictions & Visualization:** See results in `4_Final_Analysis.ipynb`.

## 🚀 Future Improvements
- Implementing **deep learning models** like CNNs for automated feature extraction.
- Using **Bayesian Optimization** for hyperparameter tuning.
- Expanding the dataset with additional exoplanet discoveries.

## 🤝 Contributions
Feel free to fork this repository, submit issues, or contribute via pull requests. Suggestions for improvement are always welcome!

---
📌 **Author:** Aditya Kayasth
📌 **License:** MIT License

