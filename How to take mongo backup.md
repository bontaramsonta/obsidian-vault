# Mongo backup
### for dumping the bson contents
```sh
mongodump -d <dbname> <mongo-uri>
```

### for a clean restore
```sh
mongorestore -v --dir ./dump --drop --uri <mongo-uri>
```