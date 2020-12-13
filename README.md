# docker-django

### ローカル環境
- docker 19.03
- docker-compose 1.27.4
- git 2.17

### 作成する環境
- Python 3.8.5
- MySQL 8.0
- nginx 1.18
- composer 1.10

### サービスの構築
```
$ docker-compose build
```

### コンテナの作成と立ち上げ
```
$ docker-compose up
```

### アプリのコンテナに接続
```
$ docker-compose exec app bash
```

### Djangoインストールコマンド
```
$ docker-compose exec app django-admin.py startproject app .
```