# k8s-citus

## 

1) change password
2) change namespace
3) change storage value

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
