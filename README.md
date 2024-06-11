# BisharBazaarBlog

## Project Description

BisharBazaarBlog is a blog platform where users can create, view, update, and delete blog posts. Users can also comment on posts.

## Technologies Used

- HTML, CSS, JavaScript
- Python, Django
- PostgreSQL
- Heroku

## Features

- User registration and login
- CRUD operations for blog posts
- Commenting system
- Responsive design

## Setup and Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Abdirizak0/BisharBazaarBlog.git
    cd BisharBazaarBlog
    ```

2. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Set up the environment variables in a `.env` file:
    ```sh
    SECRET_KEY=your_secret_key
    DEBUG=True
    DATABASE_URL=postgres://nlovytsr:wbExrZs22LkixXwa74-2lEtuMFZzcpsn@delicate-quince.db.elephantsql.com/nlovytsr
    ```

4. Set up the database:
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Create a superuser:
    ```sh
    python manage.py createsuperuser
    ```

6. Run the server:
    ```sh
    python manage.py runserver
    ```

## Usage

- Visit the registration page to create an account.
- Log in with your credentials.
- Create, view, update, and delete blog posts.
- Comment on blog posts.

## Testing

To run the tests:
```sh
python manage.py test
