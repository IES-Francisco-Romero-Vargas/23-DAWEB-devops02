# Nombre del repo

Descripción del repo

Explicación de como lanzar la apliación, etc.

## En local
```
$ gunicorn --chdir src app:app --bind 0.0.0.0:5000
```

## Usando docker
```
$ docker build -t user/devops . 
$ docker run -d -p 80:5000 --name devops2 user/devops
```

## Compose
```
$ docker compose up -d 
```



