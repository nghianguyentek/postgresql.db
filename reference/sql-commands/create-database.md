# `CREATE DATABASE` SQL Command

Create a new database.

## Steps

1. From `root` user, switch to `postgres` user and run `psql`
2. Select one:
   - [Create a database supporting Vietnamese](#create-a-database-supporting-vietnamese)

## Create a database supporting Vietnamese

`CREATE DATABASE name WITH ENCODING = 'UTF8' LC_COLLATE='vi_VN.UTF8' LC_CTYPE='vi_VN.UTF8' TEMPLATE=template0;`

### Examples

- `CREATE DATABASE test WITH ENCODING = 'UTF8' LC_COLLATE='vi_VN.UTF8' LC_CTYPE='vi_VN.UTF8' TEMPLATE=template0;`
- `CREATE DATABASE dev WITH ENCODING = 'UTF8' LC_COLLATE='vi_VN.UTF8' LC_CTYPE='vi_VN.UTF8' TEMPLATE=template0;`