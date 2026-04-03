# Django Login and Registration System

A simple Django application implementing user authentication with **login**, **registration**, and **admin panel** features. Designed with a modern dark theme and flash messages.

## Features

- User registration with email and password
- User login and logout
- Flash messages (auto-fade after 3s)
- Admin panel access
- Modern dark theme, responsive layout

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/djangoLoginRegister.git
cd djangoLoginRegister
```
### 2. Create & Activate Virtual Environment
```
python -m venv venv
```
##### Windows
```
venv\Scripts\activate
```
##### Mac/Linux
```
source venv/bin/activate
```
### 3. Upgrade pip
```
python -m pip install --upgrade pip
```
### 4. Install Dependencies
```
pip install -r requirements.txt
```
### 5. Run Migrations
```
python manage.py makemigrations
python manage.py migrate
```
### 6. Create a Superuser (for Admin Panel)
```
python manage.py createsuperuser
```
### 7. Run the Development Server
```
python manage.py runserver
```
