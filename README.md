# Ansible role: Apache

## Synopsis

Installs and configures Apache HTTP server on Ubuntu systems.

### Role variables

```
apache_user: ${APACHE_RUN_USER}
apache_group: ${APACHE_RUN_GROUP}
```

User and group using to run an Apache instance.

```
apache_server_tokens: Prod
```

Determines what informations should be returned about the server.

```
apache_enable_modules: []
apache_disable_modules: []
```

What modules should be enabled and disabled.
