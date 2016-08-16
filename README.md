# httpd for Daniel on Docker
### Install docker-compose
https://docs.docker.com/compose/install/

### Settings
    $ cp .env.template .env
    $ vi .env # Edit
    $ source set_environments .env

### Run containers
    $ export HTTPD_EXTERNAL_PORT=[port]
    $ docker-compose up -d
