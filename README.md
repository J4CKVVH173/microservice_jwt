# Микросервис для работы с jwt (JSON Web Token)

1. `python manage.py migrate`
2. `python manage.py createsuperuser`
3. `python manage.py runserver`
4. В соседнем терминале `curl -X POST -d "username=a&password=a" http://localhost:8000/api-token-auth/`
5. Команда для проверки токена `curl -X POST -H "Content-Type: application/json" -d '{"token":"<EXISTING_TOKEN>"}' http://localhost:8000/api-token-verify/`
6. Скопировать токен и вставить в [онлайн парселку](https://jwt.io/)
