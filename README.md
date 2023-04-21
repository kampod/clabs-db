# postgresql by docker-compose

1. Create the volume with docker:
```bash
    $ docker volume create --name=postgres_db_volume
```

2. Run container with docker-compose:
```bash
    $ docker-compose up -d
```

3. Stop container with docker-compose:
```bash
    $ docker-compose down
```
