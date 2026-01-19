## Nginx docker site
Суть репозитория упростить самому себе жизнь
Следующий скрипт копирует содержимое репозитория и запускает docker с веб сервером nginx
Подходит для небольших сайтов 

## Скрипт-установщик
```bash
cd /opt/
mkdir site
cd site
wget https://github.com/Sinwinz/Nginx-docker-site.git
docker compose up -d
```
