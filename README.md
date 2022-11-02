# Project UH-Drill

### ローカル環境
- docker 20.10.20
- docker-compose 2.12.1
- git 2.34.1

### 作成する環境
- Python 3.11.0
- PostgreSQL 15
- nginx 1.23.2

### 環境の構築
```
$ git clone https://github.com/uhmfg-yuyasaito/drill001.git
```

### コンテナの構築
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
