1. `python manage.py migrate`
2. `python manage.py createsuperuser`
3. `python manage.py runserver`
4. В соседнем терминале `curl -X POST -d "username=a&password=a" http://localhost:8000/api-token-auth/`
5. Скопировать токен и вставить в [онлайн парселку](https://jwt.io/)