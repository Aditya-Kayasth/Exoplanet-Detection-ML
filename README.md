# Hunting Exoplanets in Space using Machine Learning
---

## 🌌 Project Overview
This project aims to detect exoplanets using data from NASA's **Kepler Space Telescope**. The primary technique employed is the **Transit Method**, which identifies planets by observing periodic dips in a star's brightness as a planet passes in front of it. The project involves **data preprocessing, feature engineering, model training, and evaluation** using machine learning algorithms such as **Random Forest and XGBoost**.

## 📁 Repository Structure
- **`Exploring.ipynb`** - Understanding the dataset with slicing, feature analysis, visualizations, and GIF-based insights.
- **`Visualization.ipynb`** - Applying matplotlib and seaborn for pattern recognition and feature importance analysis.
- **`Normalization.ipynb`** - Implementing multiple normalization techniques, including mean normalization, to improve model performance.
- **`Model_deployment.ipynb`** - Training and evaluating Random Forest and XGBoost models before and after normalization.
- **`Fast_Fourier_Transformation.ipynb`** - Applying FFT on normalized data to extract meaningful features and enhance model accuracy.

## 🔍 Key Insights & Findings
1. **Data Exploration & Visualization**: Initial exploration with slicing and feature analysis revealed patterns in the dataset.
2. **First Model Deployment**: Random Forest and XGBoost classifiers showed 99% accuracy but failed to generalize effectively.
3. **Data Normalization**: Mean normalization slightly improved model performance, but results were still suboptimal.
4. **FFT Application**: Transforming data using FFT led to feature extraction that significantly improved XGBoost performance.

## 🚀 How to Run the Notebooks
1. Clone the repository:
   ```sh
   git clone <repo_link>
   cd <repo_folder>
   ```

2. Run the Jupyter notebooks:
   ```sh
   jupyter notebook
   ```
3. Open each `.ipynb` file to explore different stages of the analysis.

## 📊 Technologies & Libraries Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost & Random Forest
- Fast Fourier Transformation (FFT)

## 📢 Conclusion
This project showcases a structured approach to data analysis and machine learning. While standard models initially struggled, FFT-based feature extraction improved classification results significantly. The findings highlight the importance of preprocessing techniques in achieving reliable model performance.

---
