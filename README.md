# cakephp3-docker
docker

### docker初回起動
```
docker-compose up -d
```

### docker接続
```bash
docker-compose exec php bash
```

### composer install
```bash
php -r "eval('?>'.file_get_contents('https://getcomposer.org/installer'));"
php composer.phar install
```
