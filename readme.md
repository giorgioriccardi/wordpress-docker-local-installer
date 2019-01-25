# Wordpress & Docker

The `docker-compose.yaml` file will setup Wordpress, MySQL & PHPMyAdmin with a single command. Run the command:

```
# To Spin Up
$ docker-compose up -d

# To Spin Down
$ docker-compose down --volumes
```

## WordPress url

`localhost:8000`

## PhpMyAdmin url

`localhost:8080`
```
user: root
password: password
db name: wordpress
```
