# dummy-data-mongodb
### How to import:
```
> cd dummy-data-mongodb

> find *.json -exec bash -c 'name="{}"; mongoimport -d symfony -c ${name%.*}  ./{}' \;
```
