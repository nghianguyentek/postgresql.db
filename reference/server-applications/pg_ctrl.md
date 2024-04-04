# `pg_ctl` Server Application

- [Start a server instance](#start-a-server-instance)
- [Stop a server instance](#stop-a-server-instance)
- [Reload server configuration](#reload-server-configuration)

## Start a server instance

`pg_ctl start -D datadir`

### Examples

```shell
pg_ctl start -D /var/lib/pgsql/data
```

## Stop a server instance

`pg_ctl stop -D datadir`

### Examples

```shell
pg_ctl stop -D /var/lib/pgsql/data
```

## Reload server configuration

`pg_ctl reload -D datadir`

### Examples

```shell
pg_ctl reload -D /var/lib/pgsql/data
```