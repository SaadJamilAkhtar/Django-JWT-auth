# Testing token based Authentication system with Django Rest Api

# URLS:

### /hello (for testing authorization output).
### /token/ (for requesting token).


# How to use:
1. install dependencies using ```pip install -r requirements.txt```
2. Create migrations using ```python3 manage.py makemigrations```
3. Run migrations ```python3 manage.py migrate```
4. Create a user ```python3 manage.py createsuperuser```
5. Run server ```python3 manage.py runserver```
6. Request token by sending post request to /token/ with params (username="----" password="----")
7. test token by sending get request to /hello with param (Authorization = "Bearer ---access token---")
8. Refresh token by sending post request to /token/refresh by sending refresh token.

