# Server Configuration

## How?

1. Edit `postgresql.conf` file or use [ALTER SYSTEM](../../reference/sql-commands/alter-system.md#alter-system-command) SQL command.
2. Run [pg_ctl reload](../../reference/server-applications/pg_ctrl.md#reload-server-configuration) shell command or [pg_reload_conf()]() SQL function.