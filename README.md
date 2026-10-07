# Joke Application Using Django

## About the Project

This is a simple Joke Application made using the Django framework.

The application uses the PyJokes package to generate and display random jokes.

## Technologies Used

- Python
- Django
- PyJokes
- HTML

## Features

- Displays a random joke
- Simple web page
- Easy to use
- Built using Django

## Installation

Install Django:

```bash
pip install django

Install PyJokes:

pip install pyjokes
Run the Project

Open the terminal in the folder containing manage.py.

Run:

python manage.py runserver

Open this link in your browser:

http://127.0.0.1:8000/
How It Works
User opens the website.
Django runs the home page.
PyJokes generates a random joke.
The joke is displayed on the screen.
Project Structure
jokeapp/
│
├── manage.py
├── jokeapp/
│   ├── settings.py
│   └── urls.py
│
└── main/
    ├── views.py
    ├── urls.py
    └── templates/
        └── main/
            └── index.html
Output

The website displays:

Random Joke

followed by a randomly generated joke.

Conclusion

This project helps in understanding the basic concepts of Django such as URLs, views, templates, and Python packages.
