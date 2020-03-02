
1-docker-compose down && docker-compose up -d
2-docker-compose exec php composer install 

phpmyadmin URL : http://localhost:8080/index.php;
user:root pass:root
WEB URL : http://localhost:8000/

DATABASE_URL=mysql://root:root@mysqldb:3306/test?serverVersion=5.7

3-docker-compose exec php ./bin/console doctrine:fixtures:load
4-docker-compose exec php ./bin/console make:entity
5-docker-compose exec php ./bin/console make:migration
6-docker-compose exec php ./bin/console d:mig:mig

user:majid@gmail.com
pass:123456


