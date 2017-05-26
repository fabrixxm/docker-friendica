docker-friendica
================

Try Friendica in Docker

# NOTE

**this repo is unmantained and unsupported**



Quickstart
----------

    $ docker build -t fabrixxm/friendica github.com/fabrixxm/docker-friendica.git
    $ docker run -p 80:80 -e ADMIN_EMAIL=test@example.com fabrixxm/friendica

Change `test@example.com` as you want.
Open `http://localhost/register` and register using same email as `ADMIN_EMAIL`.

