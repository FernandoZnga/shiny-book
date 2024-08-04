# Books Project

[![Development Project](https://img.shields.io/badge/status-development-brightgreen)](https://github.com/yourusername/yourproject)
[![Python Project](https://img.shields.io/badge/language-python-blue)](https://www.python.org/)
[![Django Project](https://img.shields.io/badge/framework-django-092e20)](https://www.djangoproject.com/)
[![Version 1.0](https://img.shields.io/badge/version-1.0-yellow)](https://github.com/yourusername/yourproject/releases)

A simple Django CRUD application for managing books.

## Requirements

- Python 3.x
- Django 3.x

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/FernandoZnga/shiny-book.git
   cd yourproject
   ```

2. **Create a virtual environment**:

    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**:

- On Windows:

    ``` bash
    venv\Scripts\activate
    ```
- On macOS and Linux

    ```bash
    source venv/bin/activate
    ```

4. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

5. **Run migrations**:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. **Create superuser (optional, for accessing the admin interface)**:

    ```bash
    python manage.py createsuperuser
    ```

7. **Run the development server**:

    ```bash
    python manage.py runserver
    ```

8. **Visit**:
[localhost](http://127.0.0.1:8000) in your broser to interact with the CRUD app

## Features

- Create, read, update and delete books
- Simple and intuitive user interface

## Project Structure

```markdown
Books/
├── Books/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── Core/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── templates/
│   └── Core/
│       ├── book_confirm_delete.html
│       ├── book_detail.html
│       ├── book_form.html
│       └── book_list.html
├── manage.py
└── requirements.txt
```

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b my-new-feature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request

## Licence

This project is licensed under the MIT License - see the [LICENSE]() file for details.

### requirements.txt

Create a `requirements.txt` file in the root of your project with the following content:

```plaintext
Django>=3.2,<4.0
```