# PgAdmin4 - Web Launcher
## This is docker-compose version of PgAdmin4, it has configured with SSL supported. Inside the repository, there are also useable `certificate` file and `private key` file.

In addition, the docker-compose file has configured default login user (linh.nguyen@ttekglobal.com/nguyenvinhlinh). Authentication modification supports with following environment variables:
* PGADMIN_DEFAULT_EMAIL
* PGADMIN_DEFAULT_PASSWORD

Beware of the volume configuration. It's a must to set up the `certificate` file and `private key file` correctly.
