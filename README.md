🎬 Movie Comments Spoiler Detection + DRF Backend
Project: from training an NLP model to integrating it into a Django REST API for a movie app.

📩 Contacts
Author: Alymbek
LinkedIn: https://www.linkedin.com/in/alymbek-ibragimov-447876336/

📋 Description
Users leave comments about movies. The NLP model automatically detects whether a comment contains a spoiler (spoiler) or not (no_spoiler).

🔧 Tech Stack
Python 3

Pandas, scikit-learn, NLTK

Multinomial Naive Bayes

Django REST Framework

🚀 Features
✅ Classifies a comment as spoiler or no_spoiler
✅ REST API to manage:

users

comments

spoiler checking

📦 Repository Structure
Movie_comments_NLP.ipynb — training and saving the model

model_movie.pkl — trained model

vec_movie — text vectorizer

backend/ — DRF project folder

🔄 How to Run
Clone the repository

git clone https://github.com/Alymbaek/Movie_comments_ML_NLP
Install dependencies

pip install -r requirements.txt
Run the backend

python manage.py runserver
Open the admin panel or use the API to post a comment and check it for spoilers.

📈 Example API Response
json
{
  "id": 2,
  "user": {
    "first_name": "alym",
    "last_name": "alym",
    "status": "simple"
  },
  "parent": null,
  "text": "Он умрёт",
  "check_comment": ["spoiler"]
}
