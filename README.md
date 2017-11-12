# Setup

### copy env
cp .env.sample .env

### copy config.php
cp ./etc/config.php.sample ./web/public/config.php
vim ./web/public/config.php
and add login, password

### run
docker-compose -f docker-compose.prod.yml up -d
