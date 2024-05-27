# Online Course Portal

This project is a Django Web Application. Online course portal for users to enroll courses and take quizzes online.


## Prerequisites

Python 3.11
Django 4.2.3

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/phanikum4r/Online_Course_Portal.git

```
### 2. Create a Virtual Environment
Create and activate a virtual environment to manage dependencies.
```
pip install virtualenv
python -m virtualenv djangoenv
source djangoenv/bin/activate  # On Windows use `djangoenv\Scripts\activate`
```
### 3. Install Dependencies
Install the required Python packages using pip.
```
python -m pip install requirements.txt
```
### 4. Apply Migrations
Generate and apply database migrations.
```
python manage.py makemigrations onlinecustomer
python manage.py migrate
```
### 5. Create admin
Generate and apply database migrations.
```
python manage.py createsuperuser
```
### 6. Run the Development Server
Start the Django development server.
```
python manage.py runserver
```
Access the application at http://localhost:8000/onlinecourse.
