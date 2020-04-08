# docker-compose-wordpress

Project Status WIP

## Description

WordPress Stack with 
- nginx
- php-fpm
- mariadb
- minio
- memcached

## Portmapping

### Nginx
http 6080
https 60443

### Minio
6090 

### Memcached
Not exposed

### Database
Not exposed

## Open Topics 
- define resources
- ssl
- passwords
- configure WordPress
  - use MeidiaPlugin with local S3 (minio)
  - use memcached 


## Resources

- https://min.io/
- https://spinupwp.com/page-caching-varnish-vs-nginx-fastcgi-cache-2018/
- https://easyengine.io/wordpress-nginx/tutorials/single-site/fastcgi-cache-with-purging/
