# Heroku Hiring App

A Flask web application for predicting an employee salary with a saved scikit-learn model.

## Features

- A form-based prediction page.
- A JSON endpoint at `POST /predict-api`.
- A `POST /predict` route that returns the salary prediction in the web page.

## Run locally

Install the dependencies from `requirements.txt`, then start the Flask app:

```bash
python app.py
```

The app loads its model from `model.pkl`. The Heroku deployment configuration is in the repository.
