 * Docker env
```
$ cp .env-example .env
```

* Laravel env
```
$ cd src
$ cp .env.example .env
```

```
$ docker-compose up -d --build
```

```
$ docker-compose exec template-project composer install
```

URL：http://127.0.0.1:10080

#### DB

* MySQL Workbench

| --- | --- |
| Host | 127.0.0.1 |
| Port | 13308 |
| User | admin |
| Pass | secret|

