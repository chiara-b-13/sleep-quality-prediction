# sleep-quality-prediction
Creating a prediction model to predict the sleep quality based on the kaggle dataset. https://www.kaggle.com/datasets/samartalwar/sleep-debt-and-screen-time-late-night-phone-habits
Keypoints: 
1. There are 2 models, one using encoding (encoding_prediction_approach.ipynb) and the other without encoding. (simple_prediction_approach.ipynb)
2. The model with encoding preformed better overall then the model without it.
- The encoding model has 85.6% in overall accuracy
- The model without encoding has 84.4% in overall accuracy
3. The sleep quality kinds include:
- Severe
    - The encoding model has 86.6% in this specific kind.
    - The model without encoding has 91.9% in this specific kind.
- Moderate
    - The encoding model has 91.5% in this specific kind.
    - The model without encoding has 93.1% in this specific kind.
- Mild
    - The encoding model has 69.6% in this specific kind.
    - The model without encoding has 74.1% in this specific kind.
- Optimal
    - The encoding model has 80.7% in this specific kind.
    - The model without encoding has 77.5% in this specific kind.