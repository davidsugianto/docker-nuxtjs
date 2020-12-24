# Setup Web Server use Bitnami Image for Vue Js Application

## OS VERSION

> You can custom OS Distro version

1. Debian 9
2. Oraclelinux 7
3. Red Hat Enterprise Linux 7

## NGINX

> You can select NGINX version

1. 1.14
2. 1.16

## WEB APPLICATION

> You can place your application in *public-html* directory

## NGINX VIRTUAL HOST

> You can place your custom virtual file _(*.conf)_ host in *nginx/vhost* directory

## REGISTER DOMAIN NAME TO THE HOST

> Windows 8/10 OS : edit file C:\Windows\System32\Drives\etc\host

> Linux/Unix OS : edit file /etc/hosts

```
docker run -it --name kebunpintar -p 3000:3000 -v /run/media/xerox/7950d9a8-d321-44a4-a45e-4ecc195fff2c/Development/IR64-Foundation/kebunpintar/frontend/kebunpintar:/app/kebunpintar node:lts-alpine sh
```
