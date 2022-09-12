# MongoImport whith Docker.

### Usar mongoImport do MongoDB com docker - Importando dbs para uso em container Docker.


```
docker cp <NAME-FILE.json> mongodb:/tmp/<NAME-FILE.json>
```

```
docker exec <NAME-CONTAINER-MONGODB> mongoimport -d <NAME-DB> -c <NAME-COLECTION> --file /tmp/<NAME-FILE.json>
```
