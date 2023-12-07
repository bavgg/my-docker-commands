# my-docker-commands

`docker run -it -p 8080:80 -p 3306:3306 -p 8001:8000 -v ~/chatty:/var/www/html --name chatty-container ubuntu_lamp:chatty /bin/bash -c "/etc/init.d/mysql start && /etc/init.d/apache2 start && /bin/bash"`

`docker exec -it 3c34512ce246 /bin/bash`

`docker rm container_name`
