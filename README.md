# Setup

cp .env.sample .env

cp ./etc/config.php.sample ./web/public/config.php
and add login, password

docker-compose -f docker-compose.prod.yml up -d
