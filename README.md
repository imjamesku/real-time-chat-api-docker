# Real Time Chat Django API

我建了一個docker-compose這樣架環境比較方便。

## Setup
To get the containers running with docker-compose:
start docker containers 
- `docker-compose up -d`

Log into the Django docker and run the migrations
- `docker exec -it real-time-chat-api_web_1 bash`
- `python manage.py makemigrations`
- `python manage.py migrate`
- `exit`

Done! The api server should be up and listening on port 8000





This repository contains the API codebase of the Real Time Chat developed with Django Channels and React. This is part of a post, that you can read [here](https://revs.runtime-revolution.com/a-simple-real-time-chat-with-django-channels-and-react-b73edc3a79f2). You can check there how to get up and running.
