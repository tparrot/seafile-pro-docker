# seafile-pro-docker
Seafile Pro docker-compose environment with customizable settings

## Content
* switch to use debian-based seaf-cli or seaf-cli package hosted on seafiles website
* applicaton proxy for internal use (webdav mounting) and correct distribution to seahub, seafdav, seafhttp and static content
* volume for static content: avatars, logos
* preconfigured elasticsearch integration
* mariadb database
* memcached
* reverse proxy configuration template
* templates for seafdav, seafevents, seafile and seahub config
* sane defaults regarding nginx timeouts, ulimits
