# Installation on AlmaLinux

PostgreSQL version 10.23

## 1. Install using `yum`

`yum install postgresql-server`

- `libpq-13.11-1.el8.alma.1.x86_64`
- `postgresql-10.23-4.module_el8.9.0+3736+952d0ed7.alma.1.x86_64`
- `postgresql-server-10.23-4.module_el8.9.0+3736+952d0ed7.alma.1.x86_64`

## 2. Initiate a database cluster

`postgresql-setup --initdb`

- `/var/lib/pgsql/data`
- `/var/lib/pgsql/initdb_postgresql.log`

## 3. Enable `postgresql` service

`systemctl enable postgresql.service`

## 4. Start database server

```bash
su postgresql
pl_ctl start -D /var/lib/pgsql/data
```

## Links

- [`pg_ctl` server application](../../../reference/server-applications/pg_ctrl.md#pgctl-server-application)