## Emotion Classification using SVM  
**A text classification model to predict emotions (sadness, joy, love, anger, fear, surprise) from textual data.**  

---

## Overview  
This project employs a Linear Support Vector Classifier (LinearSVC) to classify text into six emotion categories. The workflow includes rigorous text preprocessing, feature extraction using TF-IDF, model training, and evaluation.  

---

## Dataset  
- The dataset (`emotions.csv`) contains two columns:  
  - `text`: Input text samples.  
  - `label`: Numeric labels (0-5) mapped to emotions.  
- **Label Mapping**:  
  - `0`: Sadness | `1`: Joy | `2`: Love | `3`: Anger | `4`: Fear | `5`: Surprise  

---

## Methodology  
### Preprocessing  
1. Convert text to lowercase.  
2. Remove URLs, mentions, hashtags, punctuation, and numbers.  
3. Filter out English stopwords.  

### Model & Features  
- **TF-IDF Vectorization**: Extracts 1,000 most frequent text features.  
- **LinearSVC**: Chosen for its efficiency with high-dimensional text data.  

---

## Results  
### Performance Metrics  
- **Accuracy**: 85.67%  
 
