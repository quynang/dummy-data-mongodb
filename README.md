# dummy-data-mongodb
### How to import:
```
> cd dummy-data-mongodb

> find *.json -exec mongoimport -d symfony -c {}  ./{} \;

```
