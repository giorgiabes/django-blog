# Django Blog

A simple and customizable blog built with Django.

## Installation on Linux (Ubuntu)

Follow these steps to set up and run the project on your local machine:

```bash
# Clone the repository
git clone https://github.com/giorgiabes/django-blog.git

# Navigate into the project directory
cd django-blog

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Apply database migrations
python manage.py migrate

# Create a superuser for admin access
python manage.py createsuperuser
```
# Add Simple Posts
Go to admin panel
```bash 
http://127.0.0.1:8000/admin/
```
