## A simple Django app using Docker Compose

You may need to go inside the web container and run a migrate in order for some of the packages to work properyly. Django Sequel Explorer needs it for sure.
Ex. `docker exec -it [container ID] /bin/bash` and then `./manage.py migrate`