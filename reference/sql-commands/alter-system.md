# The `ALTER SYSTEM` SQL Command

Change a server configuration parameter.

The changes are stored in the `postgresql.auto.conf` and applied in the next server start. To apply the changes immediately, call [pg_reload_conf()]() SQL function or execute [pg_ctl reload](../server-applications/pg_ctrl.md#reload-server-configuration) server application.

## Set a parameter

`ALTER SYSTEM SET name TO value`

## Links

- [Server configurations](../../administration/configuration/README.md#server-configuration)

