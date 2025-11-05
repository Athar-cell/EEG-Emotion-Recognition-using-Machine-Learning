# EEG Emotion Recognition using Machine Learning

This project classifies human emotional states (Positive, Neutral, Negative)
from EEG brainwave data using machine learning models.

## Dataset
Kaggle: https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions  
Samples: 2132  
Features: 2548 EEG Statistical + FFT Features  
Labels: NEGATIVE, NEUTRAL, POSITIVE

## Methods Used
- Standardization (Z-Score)
- Feature Vector Modeling
- Train/Test Split (80/20)
- Classification Models:
  - Support Vector Machine (SVM)
  - Random Forest Classifier
  - Logistic Regression

## Results
| Model | Accuracy |
|------|----------|
| Random Forest | **99%** |
| SVM | 97% |
| Logistic Regression | 97% |

## Visualization
- Confusion Matrix showing classification performance
- PCA 2D brainwave emotional state cluster visualization

## Conclusion
Brainwave signals contain distinguishable emotional features.
Random Forest performed best with 99% accuracy.
The PCA plot indicates clear separation between emotional states.

## Future Research Scope
- Deep learning on raw EEG signals
- LSTM / GRU for temporal emotional patterns
- Connect to real-time emotion detection systems
