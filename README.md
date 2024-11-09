# Wine Quality Prediction System: Random Forest

## Overview
This project uses a Random Forest model to predict the quality of red and white wines based on their chemical properties. By analyzing various features such as acidity, sugar content, and alcohol level, the model aims to classify wines on a quality scale, providing valuable insights for wine producers and consumers alike.

## Dataset
- **Source**: The dataset includes attributes of red and white wines, such as acidity, chlorides, and density.
- **Target**: Quality score on a scale (typically 1–8), indicating the wine's overall rating.

## Project Structure
- **Data Preprocessing**: Data is cleaned, normalized, and split into training and test sets. Both red and white wines are analyzed, with feature scaling applied for optimal model performance.
- **Model Training**: A Random Forest model is trained separately for red and white wines, leveraging ensemble learning to improve prediction accuracy.
- **Evaluation**: Model performance evaluated using metrics like accuracy, precision, recall, and RMSE.

## Requirements
- Python libraries: `pandas`, `scikit-learn`, `numpy`, `matplotlib`

Install dependencies with:
```bash
pip install -r requirements.txt
```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Aifedayo/Random-Forest-Red-and-White-Wine-Quality.git
   ```
2. **Run the Notebook**:
   Open and run the Jupyter notebook to follow data preprocessing, model training, and evaluation steps.

## Results
- The model provides a 92% accuracy score for predicting wine quality, giving robust insights into quality factors for both red and white wines.
