# ECommerce Backend

This Django project serves as the backend for the ECommerce web application. The frontend of the application is developed using Angular and can be found [here](https://github.com/WajahatKanju/ECommerce-Front-ng).

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

This project is part of a full-stack ECommerce application. The backend is built with Django, and the frontend is built with Angular. The application uses PostgreSQL as the database.

The frontend repository can be found [here](https://github.com/WajahatKanju/ECommerce-Front-ng).

## Features

- User authentication and authorization
- Product management
- Order processing
- Cart functionality
- ...

## Getting Started

### Prerequisites

Make sure you have the following software installed before running the project:

- Python
- Django
- PostgreSQL

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/WajahatKanju/ECommerce-Backend-Django.git
    ```
2. Navigate to the project directory:
    ```bash
   cd ECommerce-Backend-Django
   ```
3. Install the Python dependencies:
    ```bash
   pip install -r requirements.txt
   ```

##  Configuration
Configure the database settings in the settings.py file. Update the following section with your PostgreSQL credentials:
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'your_database_name',
        'USER': 'your_database_user',
        'PASSWORD': 'your_database_password',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```

## Usage
1. Apply migrations:

    ```bash
    python manage.py migrate
    ```
2. Run the development server:
    
    ```bash
    python manage.py runserver
    ```

3. Access the API at http://localhost:8000

## Contributing
Feel Free to Contribute.
Contribution Guidelines would be built soon

## License
This project is licensed under the MIT License