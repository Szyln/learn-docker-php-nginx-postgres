# learn-docker-with-php-nginx-postgresSQL

使用別人的作法：![Dockerを用いてNginxをWebサーバーとし、PHP(Laravel)、DBはPostgresSQLの開発環境を作成する。](https://qiita.com/roughstorm/items/1573ea7284282d0404d0)


## volume: var/www/html
![](https://i.imgur.com/nXpPqdd.png)


## 步驟
- 先設定 `docker-compose.yml`（就可以跑了)
- 再設定 `docker/php/dockerfile`

> 如果 `dockerfile` 有更新，需要重 build，輸入 `docker-compose build` or `docker-compose up --build`


