# Docker apache2 with php7

Ligth debian version with apache2 and php7 with all extensions required. This is just a simple web server for testing, if you want to debug and a fully development box, please check [magento2devbox-web](https://github.com/talosdigital/magento2devbox-web)


# Usage

```
docker run --name apache2php7 -dit --restart unless-stopped -p 80:80 -v ~/workspace/:/var/www/html talosdigital/apache2php7
```
