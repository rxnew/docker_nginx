# httpd for Daniel on Docker
### Install docker-compose
https://docs.docker.com/compose/install/

### Dependence
[GitBuket on Docker][gitbucket]

### Settings
    $ cp .env.template .env
    $ vi .env # Edit
    $ source set_environments .env

### Run containers
    $ docker-compose up -d

[gitbucket]: ../docker_gitbucket
