## Introduction
This is a Dockerfile to build a container image for nginx and php-fpm and Phalcon, based on https://github.com/ngineered/nginx-php-fpm. It only adds Phalcon extension for it, otherwise they're same, you can follow the original readme.

## Building from source
To build from source you need to clone the git repo and run docker build:
```
git clone https://github.com/llitllie/nginx-php-fpm-phalcon
.git
docker build -t nginx-php-fpm:phalcon .
```

If you have any improvements please submit a pull request.
