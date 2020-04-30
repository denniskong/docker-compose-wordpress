# docker-compose-wordpress

Project Status WIP

## Description

### Stack
WordPress Stack with 
- nginx
- php-fpm
- mariadb
- minio
- memcached

generating a local development environment with target AWS with S3 as media storage

### Benefits
- Speeds up generating clones and development environments since the technolgy stack which is used is the same.
- Mimicks stateless part of the stack => application server (php-fpm)


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
  - use memcached 


## Resources

- https://min.io/
- https://spinupwp.com/page-caching-varnish-vs-nginx-fastcgi-cache-2018/
- https://easyengine.io/wordpress-nginx/tutorials/single-site/fastcgi-cache-with-purging/
- https://github.com/deliciousbrains/wp-amazon-s3-and-cloudfront-tweaks
