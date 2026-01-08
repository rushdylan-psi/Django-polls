# Django Polls App

A polling application built with Django, following the official Django tutorial. This project demonstrates core Django concepts including models, views, templates, and the admin interface.

## Features

- Create and manage polls through Django admin
- Vote on poll choices
- View real-time voting results
- Custom admin interface styling

## Tech Stack

- Python 3.13
- Django 6.0.1

## Getting Started

### Prerequisites

- Python 3.10+
- pip

### Installation

1. Clone the repository
   
   git clone https://github.com/rushdylan-psi/Django-polls.git
   cd Django-polls
   2. Create and activate a virtual environment
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   3. Install dependencies
   pip install -r requirements.txt
   4. Set up environment variables
   cp .env.example .env
   # Edit .env and add your SECRET_KEY
   5. Run migrations
   python manage.py migrate
   6. Create a superuser (for admin access)
   python manage.py createsuperuser
   7. Start the development server
   python manage.py runserver
   ## Usage

- **Polls**: http://127.0.0.1:8000/polls/
- **Admin**: http://127.0.0.1:8000/admin/

## License

This project is for educational purposes.
