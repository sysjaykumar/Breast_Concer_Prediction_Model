# Breast Cancer Prediction

This project predicts whether a breast tumor is **malignant** or **benign** using machine learning techniques.  
It involves **data preprocessing**, **feature engineering**, and **model training** on a labeled dataset.

## 📂 Project Structure
- **Breast_Concer_Prediction.ipynb** — Jupyter Notebook containing the full code, explanations, and visualizations.

## 📊 Dataset
The dataset contains multiple features computed from digitized images of fine needle aspirates (FNA) of breast masses.  
These features describe the characteristics of the cell nuclei present in the image.

Typical attributes include:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

The target variable is:
- **0** — Benign  
- **1** — Malignant

## ⚙️ Workflow
1. **Data Collection & Preprocessing**
   - Load dataset
   - Handle missing values
   - Encode categorical data (if any)
   - Feature scaling/normalization

2. **Data Splitting**
   - Train/test split to evaluate model performance

3. **Model Building**
   - Train various classifiers (e.g., Logistic Regression, Random Forest, SVM)
   - Compare results

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix visualization

5. **Prediction**
   - Predict new cases based on trained model

## 🛠 Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🚀 How to Run
1. Clone the repository or download the `.ipynb` file.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Breast_Concer_Prediction.ipynb
   ```
4. Run all cells in order.

## 📈 Results
The model achieved high accuracy in distinguishing between malignant and benign cases, showing strong potential as a diagnostic aid.

## 📜 License
This project is open-source and available for educational purposes.
