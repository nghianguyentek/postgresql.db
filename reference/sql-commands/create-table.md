# `CREATE TABLE` SQL Command

Define a new table.

## Create a simple table

```
CREATE TABLE name (
    column_definitions
    [,table_constraints]
);
```

### Examples

```
CREATE TABLE test (
    id INT PRIMARY KEY,
    value VARCHAR(64) NOT NULL
);
```

### `column_definitions`

A comma-separated [column_definition](#column-definition) list

### Column definition

column_name type [column_constraint](#column-constraint)

### Column constraint

- `NOT NULL`
- `DEAULT value`
- `PRIMARY KEY`
- `REFERENCES ref_table_name(ref_column_name)`
- `UNIQUE`