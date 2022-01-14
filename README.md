# codex

## Запуск
1. docker-compose build
2. docker-compose up -d
3. Пока нет регистрации пользователей, поэтому нужно создать пользователя через админку, чтобы залогиниться - для этого нужно зайти в контейнер codex_back (docker exec -it <container id> bash) и выполнить команду python manage.py createsuperuser
4. Зайти в браузере на localhost:8000/admin и залогиниться только что созданным суперюзером
5. Users -> add user, создать пользователя
6. Зайти в браузере на localhost:3000, залогиниться только что созданным пользователем
