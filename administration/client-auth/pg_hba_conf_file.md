# The `pg_hba.conf` File

*hba stands for Host-Based Authentication*

## Content

### Default

```text
# TYPE  DATABASE        USER            ADDRESS                 METHOD
local   all             all                                     peer
host    all             all             127.0.0.1/32            ident
host    all             all             ::1/128                 ident
local   replication     all                                     peer
host    replication     all             127.0.0.1/32            ident
host    replication     all             ::1/128                 ident
```

## Methods

- [trust](#trust-method)
- [scram-sha-256](#scram-sha-256-password-authentication-method)
- ident
- peer

### `trust` method

*Only use for TCP/IP connections from localhost*

Everyone who can connect to the server can access the configured database(s).

#### Examples

```text
# TYPE  DATABASE        USER            ADDRESS                 METHOD
host    dev             dev             127.0.0.1/32            trust
```

### `scram-sha-256` password authentication method

*Only use for TCP/IP connections from localhost with database roles instead of OS users*



## Map users

``