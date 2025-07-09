# Emotion Annotation with HuggingFace Dataset

This project is part of a personal NLP learning series, focusing on practical hands-on tasks to build foundational understanding.

In this exercise, I worked with the `emotion` dataset from HuggingFace, which contains English-language tweets labeled with one of six emotions:  
- `0`: sadness  
- `1`: joy  
- `2`: love  
- `3`: anger  
- `4`: fear  
- `5`: surprise  

### Project Workflow:
- Loaded and explored the dataset using `datasets` from HuggingFace.
- Took a random sample of 20 tweets from the training split.
- Saved the tweets to a `.txt` file for manual annotation.
- Annotated each tweet manually using the defined emotion labels.
- Uploaded the labeled data back and compared it with the original labels.
- Calculated **Cohen’s Kappa** score using `sklearn.metrics.cohen_kappa_score` to measure annotation agreement.
- Visualized the agreement using a **confusion matrix** with `sklearn.metrics.ConfusionMatrixDisplay`.
- Mapped numerical labels to their corresponding emotion strings for easier interpretation.

### Tools & Libraries Used:
- Python  
- HuggingFace Datasets  
- scikit-learn  
- Google Colab (for execution and file handling)
