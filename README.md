# Seifer 

### Install
> Golang 1.12 and mkae go_mod be ON

1. Create a DB called selfile in Postgres
2. Run the DDL SQL to create the DB table
3. Add `config.json` in root directory with below reference
```json
{
    "addr": "127.0.0.1",
    "port": "2333",
    "database": {
        "connection": "postgresql://pguser:pgpassword@localhost/seifer"
    }
}
```
4. Run below commands to install/run the go server
```shell
go run main.go
```


