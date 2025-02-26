# Django Blogger Project

A full-stack blogging platform built with Django where users can create, edit, and delete tweets with images.

## Features

- User authentication (login/register)
- Create tweets with text and images
- Edit and delete your own tweets
- Responsive UI using Bootstrap
- Image upload functionality

## Installation

1. Clone the repository
```bash
git clone <repository-url>
cd "Django Full stack project"
```

2. Create a virtual environment
```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Configure environment variables
Create a `.env` file in the root directory:
```env
SECRET_KEY=your_secret_key
DEBUG=True
ALLOWED_HOSTS=localhost,127.0.0.1
```

5. Run migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

6. Create superuser (admin)
```bash
python manage.py createsuperuser
```

7. Run the development server
```bash
python manage.py runserver
```

## Project Structure

```
Blogger/
├── Blogger/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── tweet/
│   ├── templates/
│   │   └── tweet_list.html
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── media/
├── static/
├── manage.py
└── requirements.txt
```

## Usage

- Access the application at `http://127.0.0.1:8000/tweet/`
- Register a new account or login
- Create new tweets using the "Create a Tweet" button
- Edit or delete your own tweets using the respective buttons

## Technology Stack

- Python 3.x
- Django 4.x
- Bootstrap 5
- SQLite (default database)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

