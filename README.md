# This docker configuration shows that we can use ENV variable from Dockerfile in php container that have php.ini with variable as value.

1. `docker compose up -d --build`
2. `php -i|grep timezone`
