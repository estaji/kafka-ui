# About
This is a Kafka-UI and Nginx docker compose file.

UI for Apache Kafka is a simple tool that makes your data flows observable, helps find and troubleshoot issues faster and delivers optimal performance.

Official website:

https://docs.kafka-ui.provectus.io/

More examples:

https://github.com/provectus/kafka-ui/blob/master/documentation/compose/DOCKER_COMPOSE.md

There are two different deployment methods in this repo:
+ Basic authentication (Single user) + Nginx : It's suitable for testing/staging environments
+ Role-based authentication (Multi-user) using LDAP server : It's for production environments. You can use an external LDAP server or like this example, use a container-based LDAP server. Also it's possible to build your own LDAP server image based on existing ones like this repo:

    https://github.com/rroemhild/docker-test-openldap

# Installation
1.Edit user, password, port and IP sections in docker-compose.yaml and config.yaml files.

2.Use "docker compose up -d" command.

# Contribution
Feel free and don't hesitate to contribute to this repository.
