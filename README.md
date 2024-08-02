# Django Contact Management Project

This is a Django project for managing contacts and categories. It includes basic CRUD functionalities for contacts and categories, as well as user registration and update forms.

## Technologies Used

- **Django**: Web framework for developing web applications.
- **SQLite**: Lightweight relational database used for development.
- **Python**: Programming language used for development.
- **HTML/CSS**: Markup and styling languages for the frontend.

## Project Setup

### Prerequisites

Make sure you have Python and Django installed. You can install the necessary dependencies using `pip`:

```bash
pip install django


Environment Setup

1.Clone the repository:

    git clone https://github.com/MarceloHenrique7/novo-repositorio.git
    cd novo-repositorio

2.Create and activate a virtual environment (optional but recommended):

    python -m venv venv
    source venv/bin/activate  # For Windows use `venv\Scripts\activate`

3.Install the dependencies:

    pip install -r requirements.txt

4.Set up the database and apply migrations:

    python manage.py migrate

5.Create a superuser to access the admin panel:

    python manage.py createsuperuser

6.Run the development server:

    python manage.py runserver

7.Open your browser and navigate to http://127.0.0.1:8000/ to view the application.

Features
  Contact Management: Create, read, update, and delete contacts.
  Category Management: Create and manage categories for contacts.
  User Management: Register, log in, and update user profiles.
Directory Structure
  contact/: Contains the contact app, including models, views, and forms.
  project/: The main project folder with settings, URLs, and WSGI configuration.
  base_templates/: Directory for base templates.
  base_static/: Directory for static files.
  Contributing
  Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.
