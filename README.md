# Interview Weather Dockers

Run `docker compose -f 'docker-compose.yml' up -d --build` or use VS Code Docker extension to start this docker container.

A postgres DB should be started and the required tables will be created if everything is executed properly

![vscode start docker container](image.png)

One PgAdmin and Postgres DB should be running. PgAdmin can be access at http://localhost:5050, the user name is `admin@admin.com` and password is `admin`. After logging in, the weather db will ask for a password which is `weather`. Now you can view its schema

![containers](image-1.png)

DB Schema

![db cshema](image-2.png)
