# k8s-citus

## cstore

```sql
CREATE SERVER cstore_server FOREIGN DATA WRAPPER cstore_fdw;
```

```
CREATE FOREIGN TABLE {table_name}
(
  ...
)
SERVER cstore_server
OPTIONS(compression 'pglz');
```
