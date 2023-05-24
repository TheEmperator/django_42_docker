# django_42_docker
A boilerplate for a dockerized django 4.2 project<br>
<br>
This boilderplate includes the basic setup of a django proejct with postgres, redis, a gunicorn driven django project and a nginx-proxy setup.<br>
<br>
You can rename the folder of the project "django_42_docker" to whatever you want (images will be named accordingly).<br>
If you want to change the name of the django project "django_docker" to something else, you have to execute:<br>
```find . -type f -exec sed -i 's/django_docker/<your new projectname>/g' {} +```<br>
within the repository. After that you can rename the django-project directory "web/django_docker".<br>
<br>
<br>
# Setup
Requires:<br>
- docker<br>
- docker-compose<br>
<br>
Run the following command within the project:<br>
`docker-compose build` -> Creates the images<br>
`docker-compose up -d` -> Starts all containers<br>
