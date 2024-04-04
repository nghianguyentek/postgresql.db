# Authentication Configuration

- [password_encryption](#passwordencryption-mode)

## `password_encryption` mode

- `md5` (default)
- `scram-sha-256`

### Examples

`ALTER SYSTEM SET password_encryption TO 'scram-sha-256';`

### Links

- The [ALTER SYSTEM](../../reference/sql-commands/alter-system.md#set-a-parameter) SQL command