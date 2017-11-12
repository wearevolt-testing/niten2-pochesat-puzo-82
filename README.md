# Setup
$ Template for deploy php sites

### Copy env
cp .env.sample .env

### Copy config.php
cp ./etc/config.php.sample ./web/public/config.php
vim ./web/public/config.php
and add login, password

### Add php files in web

### Run
docker-compose -f docker-compose.prod.yml up -d

