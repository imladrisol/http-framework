# http-framework

```docker run nginx:1.21-alpine ls```		выведет список файлов из имеджа															
```docker-compose up -d```																	
```docker-compose build --pull```																	
```make init``` - запускает комманду init из мейк файла																	
```docker-compose exec php-fpm php -v``` 			запуск консольной комманды вывода версии пхп в контейнере php-fpm					exec работает с уже запущенный сервисом									
```docker-compose run --rm php-cli php -v``` 																	
```docker-compose run --rm php-cli composer init```																	
```docker-compose run --rm php-cli composer dump-autoload```																	
```docker-compose run --rm php-cli composer install --no-dev```																	
```docker-compose run --rm php-cli composer require --dev phpunit/phpunit```																	
```docker-compose run --rm php-cli ./vendor/bin/phpunit```				run tests													
```docker-compose run --rm php-cli ./vendor/bin/phpunit --generate-configuration```																	
```docker-compose run --rm php-cli ./vendor/bin/phpunit --colors=always	``` run tests with colors												
```docker-compose run --rm php-cli composer test ```add to composer												
```make test```																	

																	
																	
																	
