## django_setup
- This script automates the setup of a Django project with PostgreSQL and environment variable management using `.env` files. 
- It streamlines the process of creating a virtual environment, installing required dependencies, configuring database settings, and generating necessary project files.

## Usage
### 1. Clone the Repository
```bash
git clone git@github.com:PritomKarmokar/django_setup.git
```
### 2.Run the Initialization Script
```bash
chmod +x init_django_project.sh
./init_django_project.sh <project_name>
```
### 3.Activate the virtual environment
```bash
source venv/bin/activate # for linux
```
### 4. Update the `.env` according to your configuration
### 5. Run the `migration`
```bash
python manange.py migrate
``` 
### 6. Run the `server`
```bash
python manage.py runserver
```