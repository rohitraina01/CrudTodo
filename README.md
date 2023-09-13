# CrudTodo
Basic crud Todo application using python - flask and PgSql. Deployment ready using docker, docker compose

steps to run the application:-
1 - docker build -t todo_backend .  # creates docker container for backend 
2 - docker build -t todo_psql .     # creates docker container for pgsql database
3 - docker compose up               # builds connection between the containers and run them 
