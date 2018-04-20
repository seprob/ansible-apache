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

```
apache_timeot: 45
```

Setting this parameter to 45 means that the server has a maximum of 45 second to fulfill each request.

```
apache_keepalive: On
```

If you set this directive to "On" it will allow each connection to rmain open to handle multiple requests from the same client.

```
apache_max_keep_alive_requests: 100
```

Controls how many separate requests each connection will handle before ending.

```
apache_keep_alive_timeout: 5
```

How to wait for the next request after finishing the last one.
