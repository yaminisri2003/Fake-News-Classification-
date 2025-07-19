## Fake News Classification Web App using Django & NLP
This Django-based web application classifies news articles as Fake or Real using NLP (Natural Language Processing) and a trained Machine Learning model.

# Features
- Input custom news articles for classification
- Text preprocessing (lowercasing, punctuation removal, stopword filtering)
- ML model predicts whether the article is fake or real
- Web interface built using Django
  
# Technologies Used
- **Backend**: Django (Python Web Framework)
- **Machine Learning**: Scikit-learn
- **Text Processing**: TF-IDF Vectorizer, NLTK
- **Frontend**: HTML, CSS (via Django templates)

  # Dataset
The dataset used for model training includes labeled news articles with `title`, `text`, and `label` fields.
> **Note:** The dataset is not included in this repository due to size or privacy constraints. You can use any fake news dataset available on platforms like Kaggle or your custom dataset.
>
> # Set up a virtual environment:
python -m venv venv
venv\Scripts\activate  # On Windows

# Install the required packages:
pip install -r requirements.txt

# Run the Django server:
python manage.py runserver

# Model Performance
Accuracy: ~94% (or your final result)
Model Used: Logistic Regression with TF-IDF features
Evaluation Metrics: Confusion matrix, Precision, Recall
[SCREENSHOTS.docx](https://github.com/user-attachments/files/21327876/SCREENSHOTS.docx)
