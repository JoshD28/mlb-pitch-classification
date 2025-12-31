# MLB Pitch Classification

This repository focused on **classifying MLB pitch types** using **pitch-level tracking data** and **supervised learning methods**. The goal is to build, evaluate, and interpret a classification model that predicts pitch type based on physical and movement characteristics.

##Goals
1. **Build a pitch classification model** to predict pitch type using pitch-level tracking variables.
2. **Preprocess and engineer features** relevant to pitch movement and release characteristics.
3. **Evaluate model performance** using appropriate classification metrics.
4. **Interpret model results** to understand which features are most informative for pitch classification.

## Data
- **Source:** MLB pitch-level tracking data (e.g., Statcast-style variables)
- **Observations:** Individual pitches
- **Target variable:** Pitch type (e.g., fastball, slider, curveball, etc.)
- **Typical features:**  
  - Release speed  
  - Spin rate  
  - Horizontal and vertical movement  
  - Release position (as available)

## Methods
- **Modeling approach:** Supervised classification  
  (specific algorithms used are detailed in the notebook)
- **Preprocessing:**  
  - Feature selection  
  - Scaling/normalization (where appropriate)  
  - Train/test split
- **Evaluation metrics (examples):**  
  - Accuracy  
  - Confusion matrix  
  - Precision / Recall  
  - Model diagnostics and error analysis

## Outputs
- Trained pitch classification model
- Model evaluation metrics and visualizations
- Feature importance or coefficient interpretation (model-dependent)
- Summary of classification performance across pitch types

## How to Run
1. Clone or download this repository.
2. Open the notebook:
   - `Pitch_Classification_Model_in_the_MLB.ipynb`
3. Run all cells sequentially to reproduce the analysis.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn

## Notes
The focus is on **pitch type classification**, not pitcher intent or deception.  
Model performance reflects separability of pitch types based on available tracking features.
