# odoo-11-docker-compose
Odoo 11 Basic install with docker compose

# Usage

Change the folder permission to make sure that the container is able to access the directory:
```
$ sudo chmod -R 777 addons
$ sudo chmod -R 777 etc
```

Start the container:
```
$ docker-compose up
```

* Then open `localhost:8070` to access Odoo 11.0. If you want to start the server with a different port, change **8070** to another value in **docker-compose.yml**
```
$ docker-compose up -d
```

* Log file is printed @ **etc/odoo-server.log**

# Custom addons

The **addons** folder contains custom addons. Just put your custom addons here.

# Odoo configuration

To change Odoo configuration, edit file: **etc/odoo.conf**.

# docker-compose.yml

* odoo:11
* postgres:9.5

