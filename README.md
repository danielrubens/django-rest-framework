# Django Rest Framework
This is a DRF project including database core, unit test and docker.
***

## Prerequisites
- Python=>3.10

## Considerations
Requests to the API in [Curl](https://curl.se/) and [Httpie](https://httpie.io/). 

[Httpie](https://httpie.io/) provides a clean terminal output which is handy for this type of project. You will need to install it locally if you want to use the commands.
>Note: [Httpie](https://httpie.io/) is pre-installed in the docker container.
***

## Getting started
```
bash
pip install requirements.txt
python -m venv venv
docker-compose up -d --build
source venv/bin/activate
cd backend
python manage.py runserver
```
