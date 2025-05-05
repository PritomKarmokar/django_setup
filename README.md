## django_setup
- This script automates the setup of a Django project with PostgreSQL and environment variable management using `.env` files. 
- It streamlines the process of creating a virtual environment, installing required dependencies, configuring database settings, and generating necessary project files.

## Usage
### 1. Copy `init_django_project.sh` script \& `requirements.txt` file
- Then run the following commands
```bash
chmod +x init_django_project.sh
./init_django_project.sh `<project_name>`
```
### 2. Activate the virtual environment
```bash
source venv/bin/activate # for linux
```
### 3. Update the `.env` according to your configuration
### 4. Run the `migration`
```bash
python manange.py migrate
``` 
### 5. Run the `server`
```bash
python manage.py runserver
```