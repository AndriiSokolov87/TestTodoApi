# TEST DJANGO TODO API

### Deploy
1. Create virtual environment with: `python3 -m venv venv` and install dependencies by: `pip install -r requirements.txt`

2. Configure your .env file by .env.example.

| Variables                 | Description                                                                                                 |
|---------------------------|-------------------------------------------------------------------------------------------------------------|
| `SECRET_KEY`              | Django secret key. Recommended to generate with `secrets.token_urlsafe(chars_number)`.                      |
| `DEBUG`                   | Debug mode. Disable in production. May be `True` or `False`, by default, `True`.                            |
| `DATABASE_URL`            | DB connection URL. Example: `postgres://<DB_USER>:<DB_USER_PASSWORD>@<DB_HOST>:<DB_PORT>/<DB_NAME>`         |

3. Run migrations `python manage.py migrate`
   
4. Run it with `python manage.py runserver`
