# Optimized MySQL & MariaDB

Optimized my.cnf configuration for MySQL & MariaDB (on Ubuntu, CentOS etc. servers)

## Description config

Don't forget backup you old config before use this config.

The settings provided are a starting point for a 1GB - 2GB of RAM server with 1-2 CPU cores.
You can edit value follow comment in line recommend.

Or can use tools checking value config for you resources.

- https://github.com/major/MySQLTuner-perl

If you have mysql different version you should check path for log & socket or other in you version & OS.

Don't forget you resources not have 1 service(mysql)
You should keep resources for other service usage such as Apache, Nginx, php-fpm, DNS & mail server.

### Update

- Date: 8 May 2020
