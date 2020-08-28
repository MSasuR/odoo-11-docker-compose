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
$ docker-compose up -d
```
* Log file is printed @ **etc/odoo-server.log**

# Custom addons

The **addons** folder contains custom addons. Just put your custom addons if you have any.

# Odoo configuration

To change Odoo configuration, edit file: **etc/odoo.conf**.

# docker-compose.yml

* odoo:13.0
* postgres:12

