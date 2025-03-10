# 📊 Human Activity Recognition - Data Processing & Analysis Pipeline

## 📌 Overview
This project implements a **data processing and analysis pipeline** for the [Human Activity Recognition Using Smartphones Dataset](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones). It covers:
- **Data extraction, cleaning, and transformation**
- **Feature selection & dimensionality reduction**
- **Machine learning & deep learning model training**
- **Model evaluation & interpretability**
- **Data visualization & result reporting**

## 📂 Dataset
The dataset consists of sensor readings from smartphones while users perform six different activities:
1. WALKING
2. WALKING_UPSTAIRS
3. WALKING_DOWNSTAIRS
4. SITTING
5. STANDING
6. LAYING

It contains:
- **Triaxial acceleration and angular velocity** from smartphone sensors
- **561 feature variables** extracted from raw sensor data
- **Train/test labels** for activity recognition

## 🚀 Features
- **Data Preprocessing**: Standardization, normalization, feature extraction.
- **Feature Selection**: Uses PCA and RFECV for dimensionality reduction.
- **Model Training**: Implements SVM and Neural Networks.
- **Evaluation Metrics**: Classification reports, confusion matrices, ROC curves.
- **Visualization**: Plots activity trends and model performance.

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, TensorFlow, Scikit-Learn, Matplotlib, Seaborn, Lime, SHAP, Bokeh



## 🏗️ Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/human-activity-recognition.git
   cd human-activity-recognition
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Download the Dataset**
   - Access the dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones).
   - Extract the contents into the `data/` directory.

4. **Run Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## 📊 Model Training & Evaluation
- Open the **Jupyter Notebook** in the `notebooks/` folder.
- Execute cells to process data, train models, and evaluate performance.
- **Save trained models**:
  ```python
  model.save("models/activity_recognition_model.h5")
  ```
- **Export predictions**:
  ```python
  predictions.to_csv("data/predictions.csv", index=False)
  ```

## 🔍 Results & Visualizations
The project provides:
- **Confusion Matrices & Classification Reports**
- **ROC Curves & Precision-Recall Metrics**
- **LIME & SHAP Interpretability Visualizations**

## 🤝 Contributions
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


