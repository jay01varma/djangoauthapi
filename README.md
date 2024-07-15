# DjangoAuthAPI

DjangoAuthAPI is a complete authentication API built using Django REST Framework and Simple JWT. This project provides a robust and secure way to handle user authentication in your Django applications.

## Features

- User registration
- User login
- Token-based authentication using JWT
- Secure password hashing
- Token refresh and blacklist

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x
- Django REST Framework
- Simple JWT

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/jay01varma/djangoauthapi.git
    cd djangoauthapi
    ```

2. Create a virtual environment and activate it:

    ```bash
    mkvirtualenv authenv
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Run the development server:

    ```bash
    python manage.py runserver
    ```

### Testing the API

You can use the provided Postman collection to test the API endpoints. Import the `DjangoAuthAPI.postman_collection.json` file into Postman and use the predefined requests to interact with the API.

## Usage

- Register a new user
- Login with the registered user credentials
- Use the obtained JWT token to access protected endpoints
- Refresh the JWT token when it expires
- Blacklist the JWT token when logging out

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Django REST Framework
- Simple JWT

---

Feel free to customize this `README.md` file to better suit your project's needs!
